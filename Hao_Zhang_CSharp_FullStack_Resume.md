# 🧑‍💻 Zhang Hao

<div align="left">

📧 **Email:** qmtdlt@gmail.com  
🔗 **GitHub:** [github.com/qmtdlt](https://github.com/qmtdlt)  
🔗 **LinkedIn:** [linkedin.com/in/hao-zhang-288668156](https://www.linkedin.com/in/hao-zhang-288668156/)  
🌐 **Personal Website:** [youngforyou.top](https://youngforyou.top) 
📝 **Blog:** Technical articles on C#/.NET development

</div>

---

## 💼 Skills & Technologies

<div align="left">

| 🔧 **Tech Stack** | 🛠️ **Tools** |
|:-------------:|:----------:|
| **Languages:** C# (8+ years), C++ (3+ years), JavaScript/TypeScript (3+ years), SQL | **Frameworks:** .NET 9, ASP.NET Core, WPF, Vue.js |
| **Databases:** SQL Server, MySQL, QuestDB | **Others:** Git, REST APIs, TCP/UDP, Docker, Nginx |

</div>

---

## 🌟 My Advantages

- 🎯 **Project Leadership:** Proven ability to lead cross-functional teams and deliver complex government projects on schedule
- 🔄 **Full-stack Excellence:** 8+ years C# expertise with comprehensive desktop, web, and mobile development capabilities  
- 🚀 **Independent Delivery:** Demonstrated capability to single-handedly architect and deliver enterprise-level systems
- 🛡️ **Mission-Critical Systems:** Experience with high-stakes government applications requiring maximum reliability and security
- 📈 **Continuous Learning:** Committed to lifelong learning and staying current with emerging technologies

---

## 🏆 Key Achievements

- **🎯 Project Leadership:** Led 4-member team to deliver critical aerospace testing platform, ensuring 3-month on-site deployment success
- **🚀 Solo Development:** Independently architected and developed pilot recruitment system serving multiple institutions for 3+ years
- **🔧 System Reliability:** Achieved 99%+ uptime for production systems handling sensitive government operations
- **💡 Scalable Design:** Created modular architecture enabling rapid deployment across different organizational requirements
- **🌐 Full-Stack Expertise:** Delivered end-to-end solutions spanning desktop applications, web platforms, and embedded systems

---

## 💼 Work Experience

### 🏢 *Xi'an Xinxingma Electronic Technology Co., Ltd. (2021.05 - 2025.01)* 

#### **🔬 1. Testing Platform** *(Project Lead)*
> **Tech Stack:** ASP.NET Core 6 Web API • Vue3 + Element UI • WPF • MySQL/DM • QuestDB  
> **Environment:** CentOS  
> **Team:** 4 members (1 Backend, 1 Frontend, 1 Intern)

A B/S and C/S combined architecture project that integrates hardware control, real-time data collection, and intelligent alarm systems for government aerospace equipment testing programs.

**🎯 Core Features:**
- **📊 B/S System:**
  1. **System Configuration Management** - Test resources (hardware modules, channels, product configurations), alarm configurations, communication protocols
  2. **Device Integration** - Keysight power supplies (TCP, SCPI commands), oscilloscopes (Web Server), lower computers (UDP)
  3. **Real-time Data Processing** - SignalR push, real-time storage, intelligent alarm logic, historical data query and export

- **💻 C/S Client:**
  - WPF client optimizes B/S performance issues, supports longer time range with faster response
  - Real-time curves connect to SignalR, historical curves connect to Web API
  - High-performance chart rendering using ScottPlot components

**🚀 Project Impact:**
- Successfully delivered and deployed for critical aerospace equipment testing
- Maintained 3-month on-site deployment and optimization period
- System achieved stable production operation with 99%+ uptime
- Led cross-functional team through complete development lifecycle

#### **🧠 2. Multimodal Data Collection and Intervention System**
> **Tech Stack:** WPF • Multi-hardware Device Integration • Real-time Data Processing

A WPF-developed project designed to monitor physiological data changes of subjects in specific scenarios and provide interventions based on physiological data characteristics.

**📱 Connected Devices:**
- **Collection Devices:** Biological monitors, near-infrared devices, EEG, video cameras, eye trackers, pedal force meters, grip strength meters, and some self-developed devices
- **Output Devices:** Electric shock vibration stimulators, ear canal temperature stimulators

The system displays real-time data from collection devices, including curves, videos, and other custom components, integrates client-side model algorithms, and automatically controls output devices to complete interventions.

#### **✈️ 3. Flight Personnel Training System** *(Solo Development)*
> **Tech Stack:** ASP.NET Core 5 Web API • Vue3 + Element UI • WPF • SQL Server • Redis

A B/S and C/S combined architecture project designed for pilot recruitment testing, featuring over twenty specialized mini-programs for comprehensive candidate evaluation.

**🎮 System Architecture:**
- **B/S Side:** Mini-program version management, question bank resource updates, user and permission management
- **C/S Side:** WPF client connects to B/S backend, obtains training resources based on logged-in users, uniformly saves test data

**🔧 Technical Highlights:**
Since each mini-program runs as an independent process, the client is responsible for downloading, launching, receiving test results from mini-programs, and transparently transmitting results to server APIs. To simplify inter-process communication, before launching mini-programs, the client writes question bank data to Redis. After mini-programs test finished, test results are published through Redis, received by the client, and pushed to the server via RestClient.

**🏆 Business Impact:**
- Single-handedly developed flexible, modular system architecture
- Successfully deployed across multiple pilot recruitment institutions
- System has been in stable operation for 3+ years
- Multiple customized branches deployed for different recruitment organizations
- Flexible design enables rapid adaptation to varying testing requirements

#### **📡 4. Antenna Measurement Anechoic Chamber**
> **Tech Stack:** Qt C++ • Multi-axis Motion Control • Vector Network Analyzers • Signal Sources & Receivers • Data Visualization

A Qt C++ project developed as supporting software for microwave antenna testing laboratories. Through abstract design, it integrates different brands and models of multi-axis motion controllers, vector network analyzers (signal sources, receivers), and other equipment to achieve data collection in different test scenarios. Data visualization includes curves, heatmaps, contour lines, and 3D surfaces.

#### **🎥 5. Distributed Video Monitoring and Data Collection System**
> **Tech Stack:** ASP.NET Core Web API • WPF • TCP/UDP • Redis • ScottPlot • HTTP Client

A LAN-based distributed monitoring system that enables collaborative work across multiple computers, integrating real-time video surveillance and third-party data collection capabilities.

**🔧 System Architecture:**
- **Client Nodes:** Three computers capture real-time video via USB cameras, transmitting to the main controller via TCP protocol
- **Main Controller:** WPF client implements synchronized display and monitoring of three video streams
- **Data Collection:** Receives HTTP POST data pushes from third-party programs on other computers
- **Data Processing:** Web API receives pushed data, Redis pub/sub implements real-time notifications
- **Data Visualization:** Integrates ScottPlot components for historical data curve analysis and display

**💡 Technical Highlights:**
Low-latency video stream transmission via TCP, Redis pub/sub pattern ensures data real-time performance, WPF multi-threading ensures smooth UI responsiveness, and ScottPlot provides high-performance chart rendering capabilities.

#### **🔧 6. Other Projects**

<details>
<summary>Click to expand and view detailed projects</summary>

1. **🗺️ 2D Map System based on Qt C++ + CEF**
   - **Features:** Real-time trajectory, trajectory playback, airspace drawing
   - **Technology:** Integrates communication protocols, drives real-time data collection and display
   - **Environment:** Kylin Desktop OS

2. **🎯 Antenna Tracking Control Software**
   - **Technology:** Based on Qt C++ development
   - **Features:** Integrates network protocols, controls antenna turntable azimuth and elevation movement, parses protocol data, automatically tracks targets

3. **⛽ Natural Gas Company Asset Management System**
   - **Tech Stack:** ASP.NET Core + Vue3 + WeChat Mini Program
   - **Features:** Company asset maintenance, transfer, sale, disposal data workflows, WeChat mini program for filing and inventory

4. **🌡️ Temperature and Humidity Measurement Device Control System**
   - **Technology:** Based on WPF development
   - **Features:** Integrates with Shaanxi Provincial Institute of Metrology temperature and humidity measurement device serial protocols, obtains standard temperature and humidity, controls motion controllers, moves cameras to preset positions, captures temperature and humidity display values, compares with standard values and actual readings, generates test reports after manual verification

</details>

### 📡 *Xi'an Kelan Electronics Co., Ltd.(2020.02 - 2021.04)*

#### **🔌 Communication Room Power Supply Early Warning System**
> **Tech Stack:** ASP.NET Core • Vue.js • Third-party API Integration • Real-time Data Monitoring

A project based on ASP.NET Core + Vue development, primarily responsible for backend API implementation and related early warning logic, interfacing with frontend to realize business functions.

**⚡ Core Features:**
- **Data Integration:** Interface with third-party environmental monitoring systems for real-time data collection and import
- **Intelligent Early Warning:** Implement work behavior processing and alarm mechanisms for various power supply equipment under different scenarios

### 🏛️ *Xi'an Jinghexinda & Beijing Ruileitong Electronic Technology Co., Ltd.(2017.03 - 2019.11)*

#### **📚 Haidian Education Committee Housing Subsidy Management System**
> **Tech Stack:** ASP.NET Core MVC • LayUI • jQuery • SQL Server

Developed using ASP.NET Core MVC + LayUI + jQuery with SQL Server database, implementing online housing subsidy applications for Haidian District education staff, employee file management, application review, report export, information publication, and online printing functions.

#### **🎬 Jiecheng Huashi Wangju ERP System**
> **Tech Stack:** ASP.NET Core MVC • LayUI • jQuery • SQL Server

Developed using ASP.NET Core MVC + LayUI + jQuery, primarily for managing film and TV copyright and contract data, completing media resource information management, contract ledger management, accounts receivable/payable management, basic archives, and approval workflows with core approval logic implemented through stored procedures.

#### **🔬 Remote Monitoring Control Software**
> **Tech Stack:** MFC • UDP Communication • Serial Control

Implemented using MFC, with upper computer and lower computer communicating via UDP. The upper computer handles command sending and status monitoring, while the lower computer responds to commands, controls power supplies through serial ports, collects power data, and transmits back to the upper computer.

---

## 🎓 Education

### 🏫 Xi'an Polytechnic University *2012.09 – 2016.07*
- **Relevant Courses:** Data Structures and Algorithms, Operating Systems, Database Principles, Software Engineering

---

## 🚀 Personal Projects

#### **🌍 Online English Learning Platform** - [youngforyou.top](https://youngforyou.top)
> **Tech Stack:** ASP.NET Core • Vue.js • Azure Cognitive Services • MySQL

- **Key Features:** EPUB upload, Azure TTS audiobook generation, pronunciation scoring, AI translation, paragraph explanations and sentence evaluations (Grok, Gemini, Doubao, Qwen), vocabulary management
- **Project Demo:** [I built a website to learn English](https://www.bilibili.com/video/BV1Cw3Lz4E8e/)

#### **🎥 English Video Learning Client**
> **Tech Stack:** Avalonia • VLC • Restclient

- **Key Features:** Shares the same backend as youngforyou.top, a local movie player based on VLC development, parses SRT subtitles, click subtitles for word translation, subtitle pronunciation scoring functionality
- **Project Demo:** [Learn English by Watch English videos](https://www.bilibili.com/video/BV1k6GMz3EBv/)

---

## 🌐 Language Skills

- **Chinese:** Native  
- **English:** Professional Working Proficiency
