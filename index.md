---
layout: default
---

# I am Daniyal Akbar, a passionate Python programmer.

## What I Do

I am an IoT-focused engineer with experience in cybersecurity, python, and cloud infrastructure. I’ve worked on secure CI/CD pipelines, Kubernetes-based microservices, and security monitoring in high-assurance environments across government and defense projects.

## Resume

You can view my full background and experience here:

- [📄 Download Resume](resume-daniyal-akbar.pdf)

## Recent Projects

<!-- Here are a few projects that showcase my engineering interests and skills: -->

### Real-Time STM32 IoT Telemetry Pipeline (2025)

A complete end-to-end IoT data pipeline built from scratch, collecting real sensor data from an STM32 microcontroller and streaming it into a fully instrumented cloud dashboard.

**What I built:**

- **Embedded device firmware (STM32)**  
  Programmed the MCU to read temperature and internal sensor values, package them as JSON, and publish them over MQTT.

- **Edge → Cloud ingestion**  
  - Data transmitted to an **Azure IoT Hub** gateway.  
  - Events automatically routed into an **Azure Storage container** for raw telemetry archiving.

- **Automated data processing (Python)**  
  - Developed a real-time “blob tailer” service that continuously watches the newest blob in Azure Storage.  
  - Parses each incoming JSON record and feeds it into **InfluxDB** for time-series storage.

- **Live visualization & monitoring (Grafana)**  
  - Built a full Grafana dashboard showing STM32 temperature in real time.  
  - Added detailed field overrides (units, precision, labels), time-series charts, and upcoming stat panels for latest sensor values.  
  - Configured custom queries in Flux to filter measurement streams and extract latest device metrics.

**Outcome:**  
A cloud-ready IoT monitoring pipeline capable of collecting, transforming, storing, and visualizing microcontroller telemetry with sub-second latency. This project demonstrates expertise across embedded systems, Python data engineering, cloud ingestion patterns, time-series databases, and observability tooling.


## Get In Touch

If you’d like to talk about IoT, cloud, or security engineering opportunities, feel free to contact me:

- **Email:** [daniyal.s.akbar@gmail.com](mailto:daniyal.s.akbar@gmail.com)
- **Location:** Houston, TX
- **LinkedIn:** [linkedin.com/in/daniyalakbar](https://www.linkedin.com/in/daniyalakbar)


