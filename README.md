# 🖥️ Network PC Monitoring
 
A Java-based desktop application for real-time monitoring and control of PCs across a local network — built for exam halls, labs, and classroom environments.
 
---
 
## 📌 Overview
 
**Network PC Monitoring** (also known as `Exam_Control`) is a client-server Java Swing application that allows an administrator to monitor and manage multiple student/client machines over a network in real time. It is ideal for use in examination centers, computer labs, and educational institutions where supervisors need centralized control over connected PCs.
 
---
 
## ✨ Features
 
- 🔍 **Real-time PC Monitoring** — View the status of all connected machines on the network
- 🖥️ **Centralized Control** — Administrator can manage client PCs from a single dashboard
- 📡 **Network Communication** — Communicates over LAN for seamless multi-PC supervision
- 🔒 **Exam Environment Control** — Designed to enforce exam rules and restrict client activity
- ⚡ **Lightweight & Fast** — Built with Java Swing for a responsive desktop UI
- 📦 **Standalone JAR** — Easy to run with no complex installation required
---
 
## 🛠️ Tech Stack
 
| Technology | Purpose |
|---|---|
| **Java** | Core application language (99%+) |
| **Java Swing** | Desktop GUI framework |
| **AppFramework 1.0.3** | Application lifecycle management |
| **SwingWorker 1.1** | Background task threading |
| **JShortcut 0.4** | Windows shortcut utilities |
| **HTML** | Supplementary UI elements |
 
---
 
## 📁 Project Structure
 
```
Network-PC-Monitoring/
├── src/                        # Java source files
├── Exam_Control.jar            # Main executable JAR
├── appframework-1.0.3.jar      # App framework dependency
├── swing-worker-1.1.jar        # SwingWorker dependency
├── jshortcut-0.4-oberzalek.jar # JShortcut dependency
└── README.md
```
 
---
 
## 🚀 Getting Started
 
### Prerequisites
 
- Java JDK/JRE **8 or above** installed
- All machines on the **same local network (LAN)**
### Running the Application
 
1. Clone this repository:
   ```bash
   git clone https://github.com/Anish2124/Network-PC-Monitoring.git
   cd Network-PC-Monitoring
   ```
 
2. Run the main JAR file:
   ```bash
   java -jar Exam_Control.jar
   ```
 
> Make sure all dependency JARs (`appframework-1.0.3.jar`, `swing-worker-1.1.jar`, `jshortcut-0.4-oberzalek.jar`) are in the **same directory** as `Exam_Control.jar`.
 
### Building from Source
 
Open the project in **NetBeans IDE** (recommended) or any Java IDE of your choice, resolve the classpath dependencies, and build the project. The IDE will automatically copy all JAR dependencies to the `dist/lib/` folder.
 
---
 
## 🖥️ Usage
 
1. **Start the server (admin machine):** Launch `Exam_Control.jar` on the administrator's PC and configure the network settings.
2. **Connect client PCs:** Run the client component on each student/lab machine to establish a connection.
3. **Monitor & control:** Use the admin dashboard to view all connected machines, monitor activity, and apply controls as needed.
---
 
## ⚙️ Configuration
 
To set or change the main class in the project:
 
- Right-click the project node in NetBeans → **Properties** → **Run** → enter the class name in the **Main Class** field.
- Or manually update the `Main-Class` attribute in `MANIFEST.MF`.
---
 
## 📋 Notes
 
- If two JAR files on the classpath share the same name, only the first one is copied to the `lib` folder during build.
- Only JAR files are copied to the `lib` folder; other file types/folders are excluded.
- If a library's manifest includes a `Class-Path` entry, those paths must also be available at runtime.
---
 
## 🤝 Contributing
 
Contributions are welcome! Feel free to:
 
1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request
---
 
## 📄 License
 
This project is open-source. Feel free to use and modify it for educational purposes.
 
---
 
## 👨‍💻 Author
 
**Anish2124**
- GitHub: [@Anish2124](https://github.com/Anish2124)
---
