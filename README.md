Hi there 👋, I'm Rohit Suravajjula!

I'm an Electronics and Communication Engineering (ECE) graduate who builds at the hardware-software boundary — architecting firmware, Python pipelines, and dashboards that turn raw device data into usable output. I believe in learning by building real-world systems that solve practical problems.

Currently, I'm a BioPharma Engineering Intern (Software & Embedded Systems) at Promea Therapeutics, working in R&D / Connected Health on an industrial edge gateway that bridges a legacy medical device to a software backend for automated reporting.

## 🛠️ Skills

**Programming**
- Python
- Arduino (C/C++)

**Embedded Systems**
- ESP32-S3-N16R8
- ESP8266 (NodeMCU)
- I2C Bus Interfacing
- RFID (EM-18)
- Serial Debugging & Protocol Analysis
- TCP/IP Socket Communication

**Software Development**
- Streamlit
- Data Parsing & Processing
- PDF Report Generation (ReportLab)

**Tools**
- Git & GitHub
- VS Code
- Virtual Environments (.venv)

## 🚀 Featured Project

**Industrial Edge Gateway for Legacy Medical Devices**

Designed and built an end-to-end wireless data acquisition gateway bridging a legacy electrolyte analyzer to a software backend during R&D validation.

- Diagnosed serial communication dropouts via COM-level protocol analysis and traced the failure to a missing USB host controller — initially tested on a Wemos D1 Mini, but it lacked USB host support, so migrated to an ESP32-S3-N16R8 to resolve the gap and eliminate I2C dual-bus throughput constraints.
- Architected a two-part Python pipeline: a TCP listener for automated transmission-complete detection, and a Streamlit dashboard that auto-matches incoming data to sample records and generates diagnostic PDF reports.
- Engineered a "smart flush" mechanism that injects synthetic end-markers, cutting transmission-complete detection from multi-second timeouts to near-instant.

## 📚 Currently Learning

- Python
- Embedded Systems
- Git & GitHub Best Practices
- SQL
- Software Development

## 🎯 Career Goal

To grow as a Software Engineer / Embedded Software Engineer by building practical, production-facing systems and contributing to real-world engineering solutions.

## 📫 Connect with Me

- LinkedIn: https://www.linkedin.com/in/rohit-suravajjula-bb96a926a/
- GitHub: https://github.com/rohit-suravajjula
- Email: suravajjularohit2003@gmail.com
