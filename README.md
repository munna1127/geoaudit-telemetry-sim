# GeoAudit-Sim: Client-Side Geolocation & Network Path Telemetry Framework

An authorized Red Team simulation and social engineering susceptibility auditing portal designed to measure organizational vulnerability to client-side metadata exposure and location boundary leakage.

## 📊 Technical Execution & Methodology

1. **Unauthenticated Perimeter Probing:** Simulates an administrative gateway layer to test employee click-through vectors and security awareness compliance boundaries during phishing exercises.
2. **Asynchronous Multi-Source Network Ingestion:** Executes dual REST API queries against external cloud endpoints (`ipify.org` and `ipapi.co`) to capture core network layer metrics (Client IP Address, Autonomous System/ISP allocations, and coarse location coordinates).
3. **HTML5 Geolocation Inversion:** Interfaces with client-side Web APIs to evaluate device permission compliance models. Upon verification, gathers hardware-level GPS coordinate properties (Latitude, Longitude, and Precision Margin metrics).
4. **Exfiltration Pipeline Integration:** Utilizes encrypted asynchronous webhooks linked to the Telegram Bot API framework (`sendMessage` and `sendLocation` channels) to dispatch immediate telemetry logs to infrastructure administrators.
