# 🧑‍💻 Zhang Hao

<div align="center">

📧 **Email:** qmtdlt@gmail.com  
🔗 **GitHub:** [github.com/qmtdlt](https://github.com/qmtdlt)  
🌐 **Personal Website:** [youngforyou.top](https://youngforyou.top)

</div>

---

## 💼 Skills & Technologies

<div align="center">

| 🔧 **Tech Stack** | �️ **Tools** |
|:-------------:|:----------:|
| **Languages:** C#, C++, JavaScript (ES6+), TypeScript, SQL | **Frameworks:** .NET 9, ASP.NET Core, WPF, Vue.js |
| **Databases:** SQL Server, MySQL, QuestDB, DM Database | **Others:** Git, RESTful API, TCP/UDP, Docker, Nginx |

</div>

---

## 🌟 My Advantages

- 🎯 Adept at finding solutions in uncertain environments, driving project implementation and execution
- 🔄 Full-stack development capabilities spanning desktop, web, and WeChat mini-program development, finding commonalities across different technologies
- 🚀 Maintaining curiosity about the unknown, committed to lifelong learning

---

## 💼 Work Experience

### 🏢 *Xi'an Xinxingma Electronic Technology Co., Ltd.*

#### **🔬 1. Testing Platform**
> **Tech Stack:** ASP.NET Core 6 Web API • Vue3 + Element UI • WPF • MySQL/DM • QuestDB  
> **Environment:** CentOS • Kylin OS

A B/S and C/S combined architecture project that integrates hardware control, real-time data collection, and intelligent alarm systems.

**🎯 Core Features:**
- **📊 B/S System:**
  1. **System Configuration Management** - Test resources (hardware modules, channels, product configurations), alarm configurations, communication protocols
  2. **Device Integration** - Keysight power supplies (TCP, SCPI commands), oscilloscopes (Web Server), lower computers (UDP)
  3. **Real-time Data Processing** - SignalR push, real-time storage, intelligent alarm logic, historical data query and export

- **💻 C/S Client:**
  - WPF client optimizes B/S performance issues, supports longer time range with faster response
  - Real-time curves connect to SignalR, historical curves connect to Web API
  - High-performance chart rendering using ScottPlot components

#### **🧠 2. Multimodal Data Collection and Intervention System**
> **Tech Stack:** WPF • Multi-hardware Device Integration • Real-time Data Processing

A WPF-developed project designed to monitor physiological data changes of subjects in specific scenarios and provide interventions based on physiological data characteristics.

**📱 Connected Devices:**
- **Collection Devices:** Biological monitors, near-infrared devices, EEG, video cameras, eye trackers, pedal force meters, grip strength meters, and some self-developed devices
- **Output Devices:** Electric shock vibration stimulators, ear canal temperature stimulators

The system displays real-time data from collection devices, including curves, videos, and other custom components, integrates client-side model algorithms, and automatically controls output devices to complete interventions.

#### **✈️ 3. Portable Flight Personnel Training System**
> **Tech Stack:** ASP.NET Core 5 Web API • Vue3 + Element UI • WPF • SQL Server • Redis

A B/S and C/S combined architecture project that designed over twenty test mini-programs, each as an independent game with content controllable through question banks.

**🎮 System Architecture:**
- **B/S Side:** Mini-program version management, question bank resource updates, user and permission management
- **C/S Side:** WPF client connects to B/S backend, obtains training resources based on logged-in users, uniformly saves test data

**🔧 Technical Highlights:**
Since each mini-program runs as an independent process, the client is responsible for downloading, launching, receiving test results from mini-programs, and transparently transmitting results to server APIs. To simplify inter-process communication, before launching mini-programs, the client writes question bank data to Redis. After mini-programs load, test results are published through Redis, received by the client, and pushed to the server via RestClient.

#### **📡 4. Antenna Measurement Anechoic Chamber**
> **Tech Stack:** Qt C++ • Multi-axis Motion Control • Vector Network Analyzers • Signal Sources & Receivers • Data Visualization

A Qt C++ project developed as supporting software for microwave antenna testing laboratories. Through abstract design, it integrates different brands and models of multi-axis motion controllers, vector network analyzers (signal sources, receivers), and other equipment to achieve data collection in different test scenarios (far-field, planar near-field, cylindrical near-field). Data visualization includes curves, heatmaps, contour lines, and 3D surfaces.

#### **🔧 5. Other Projects**

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

### 📡 *Xi'an Kelan Electronics Co., Ltd.*

#### **🔌 Communication Room Power Supply Early Warning System**
> **Tech Stack:** ASP.NET Core • Vue.js • Third-party API Integration • Real-time Data Monitoring

A project based on ASP.NET Core + Vue development, primarily responsible for backend API implementation and related early warning logic, interfacing with frontend to realize business functions.

**⚡ Core Features:**
- **Data Integration:** Interface with third-party environmental monitoring systems for real-time data collection and import
- **Intelligent Early Warning:** Implement work behavior processing and alarm mechanisms for various power supply equipment under different scenarios

### 🏛️ *Xi'an Jinghexinda & Beijing Ruileitong Electronic Technology Co., Ltd.*

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

- **Key Features:** EPUB upload, Azure TTS audiobooks, pronunciation scoring, AI translation, paragraph explanation and sentence evaluation (grok, gemini, doubao, qwen), vocabulary management
- **Project Demo:** [I built a website to learn English](https://www.bilibili.com/video/BV1Cw3Lz4E8e/)

#### **🎥 English Video Learning Client**
> **Tech Stack:** Avalonia • VLC • Restclient

- **Key Features:** Shares the same backend as youngforyou.top, a local movie player based on VLC development, parses SRT subtitles, click subtitles for word translation, subtitle pronunciation scoring functionality
- **Project Demo:** [Learn English by Watch English videos](https://www.bilibili.com/video/BV1k6GMz3EBv/)

---

## 🌐 Language Skills

- **Chinese:** Native  
- **English:** Professional Working Proficiency
