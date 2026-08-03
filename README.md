# Home Assistant App: iPerf3 Server

![Home Assistant App](https://img.shields.io/badge/Home%20Assistant-Add--on-blue.svg)
![Supports aarch64 Architecture](https://img.shields.io/badge/aarch64-yes-green.svg)
![Supports amd64 Architecture](https://img.shields.io/badge/amd64-yes-green.svg)
![Supports armhf Architecture](https://img.shields.io/badge/armhf-yes-green.svg)
![Supports armv7 Architecture](https://img.shields.io/badge/armv7-yes-green.svg)

A lightweight, local **iPerf3 Server** App (Add-on) for Home Assistant. 

Local iPerf3 network performance benchmarking server for Home Assistant. Provides a persistent endpoint for measuring throughput, latency, and packet loss across LAN, WiFi, and private network infrastructure.

---

## Installation

1. Open your **Home Assistant** dashboard.
2. Navigate to **Settings** &rarr; **Apps** &rarr; **Install app**.
3. Use the **3 Dots** (top-right corner) &rarr; **Repositories** &rarr; **Add (repository)**
4. Use this GitHub repository URL:
   ```text
   https://github.com/b247/iPerf3-HA
5. **Add** to save, then return to **App store**
6. Search for **iPerf3 Server** &rarr; **Install** and **Start** the App.

## Testing Network Performance with iPerf3
Use any iPerf3 client to test against <HOME_ASSISTANT_IP>:5201. For iOS and Android, **Network Tools by Hurricane Electric** is a great option. For Linux, macOS, or Windows, you can use any suitable FOSS CLI or GUI tool.
