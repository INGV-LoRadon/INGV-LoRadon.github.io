![](ingv_logo_banner.png)

# INGV-LoRadon :: Volcano 🌋 Radon ☢️ Monitoring

LoRadon is a **low-cost, LoRaWAN-based radon monitoring system** developed at INGV for deployment on Mount Etna and other volcanic areas.
It combines **pulse-counting sensors**, **embedded systems**, and a **LoRaWAN backend** to provide real-time monitoring as an alternative to traditional high-cost stations.

![ERN4 Radon station](https://github.com/INGV-LoRadon/INGV-LoRadon.github.io/blob/eb150b909dfbbb51c82e5e5955e33d3a1282a4ba/images/20250410_130656%20(1).jpg)
---

## 📂 Repository Structure

* **Doc/** → Documentation, user manuals, TTN LoRaWAN setup, hardware references (Wyres Base, RAK3172)
* **Firmware/** → Endpoint firmware (RAK3172, Wyres Base with RIOT OS) for LoRaWAN transmission
* **Backend/** → Data processing & dashboards (Grafana, NodeRED, InfluxDB), with Docker configuration and deployment scripts

---

## 🌐 Backend Access

* **Grafana**: [loradon.oe.ingv.it](https://loradon.oe.ingv.it)
* **NodeRED**: [loradon-n.oe.ingv.it](https://loradon-n.oe.ingv.it)
* **ThingsBoard**: [loradon-t.oe.ingv.it](https://loradon-t.oe.ingv.it)

---

## 👥 Contributors

Work in progress – see `/Doc` for details.
