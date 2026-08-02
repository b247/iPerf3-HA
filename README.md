# Home Assistant Add-on: iPerf3 SpeedTest Server

[![Home Assistant Add-on](https://img.shields.io/badge/Home%20Assistant-Add--on-blue.svg)](https://www.home-assistant.io)
[![Supports aarch64 Architecture](https://img.shields.io/badge/aarch64-yes-green.svg)](https://github.com)
[![Supports amd64 Architecture](https://img.shields.io/badge/amd64-yes-green.svg)](https://github.com)

A lightweight, local **iPerf3 Server** add-on for Home Assistant. 

Local iPerf3 network performance benchmarking server for Home Assistant. Provides a persistent endpoint for measuring throughput, latency, and packet loss across LAN, WiFi, and private network infrastructure.

---

## Installation

1. Open your **Home Assistant** dashboard.
2. Navigate to **Settings** $\rightarrow$ **Add-ons** $\rightarrow$ **Add-on Store**.
3. Click the **3 Dots** (top-right corner) $\rightarrow$ Select **Repositories**.
4. Paste the GitHub repository URL:
   ```text
   https://github.com/YourUsername/ha-iperf3-addon
5. Click Add and close the repository dialog.
6. Refresh the Add-on Store, search for iPerf3 Server, and click Install.
7. Click Start.

## Testing Network Performance with iPerf3
Use any iPerf3 client to test against <HOME_ASSISTANT_IP>:9201. For iOS and Android, **Network Tools by Hurricane Electric** is a great option. For Linux, macOS, or Windows, you can use any suitable FOSS CLI or GUI tool.
