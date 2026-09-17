# Swanirbhar AI Workbench 🚀

**Your intelligent workspace for AI-powered productivity.**

Swanirbhar AI Workbench is a desktop application built with **PySide6 (Qt)** that provides a unified workspace for AI-assisted productivity, project management, document handling, system monitoring, and activity tracking.

> **Note:** The current release is a demonstration/prototype version. Some AI features are available in demo mode, with the full AI backend planned for future implementation.

---

## ✨ Features

### 📊 Dashboard
- AI assistant interface in demo mode
- Manage documents and generated output files
- Central workspace for AI-powered tasks

### 📁 Projects
- View and manage AI projects
- Grid-based project interface
- Organized project workspace

### 📈 Reports
- Generate and track reports
- Progress indicators and animations
- Report management interface

### ⚙️ Settings
- Customize application preferences
- Configure AI model settings
- Manage storage paths
- Configure privacy preferences
- Theme customization

### 🖥️ System Monitoring
Real-time monitoring of:
- CPU usage
- Memory usage
- GPU usage
- Disk usage
- Wi-Fi/network statistics

### 🕒 History
- Complete activity history
- Timestamp-based activity tracking
- Persistent JSON-based storage

### 📋 Logs
- Live application and system logs
- Color-coded log levels
- Persistent log file storage

### ❓ Help
- Built-in documentation
- Application guidance
- Support information

---

## 🖥️ Download & Installation

### Windows

Download the Windows executable from the official GitHub Release:

[Download Swanirbhar Workbench for Windows](https://github.com/ashfakalam/Swanirbhar/releases/download/v1.0.1/SwanirbharWorkbench.exe)

No Python installation or additional dependencies are required.

### Linux

A Linux **AppImage** is also available in the GitHub Releases.

[View all Swanirbhar releases](https://github.com/ashfakalam/Swanirbhar/releases)

Download the AppImage, give it executable permission, and run it:

```bash
chmod +x SwanirbharWorkbench.AppImage
./SwanirbharWorkbench.AppImage
```

---

## 👨‍💻 Team

### Team TechTitans

- **Ashfak Alam**
- **Nadia Muskan**
- **Md Shahid Iqbal**
- **Mullick Waliullah**
- **Zaid Imam**
- **Bikram Bera**

---

## 🛠️ Technology Stack

- **Python**
- **PySide6**
- **Qt**
- **JSON**
- **System Monitoring APIs**
- **PyInstaller** — Windows executable packaging
- **AppImage** — Linux distribution

---

## 🔧 Development Setup

### 1. Clone the Repository

```bash
git clone https://github.com/ashfakalam/Swanirbhar.git
cd Swanirbhar
```

### 2. Create a Virtual Environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Application

```bash
python main.py
```

---

## 📂 Project Structure

```text
Swanirbhar/
│
├── main.py
├── requirements.txt
├── README.md
│
├── assets/
│   └── ...
│
├── ui/
│   └── ...
│
├── modules/
│   ├── dashboard/
│   ├── projects/
│   ├── reports/
│   ├── settings/
│   ├── monitoring/
│   ├── history/
│   ├── logs/
│   └── help/
│
└── data/
    └── ...
```

> The exact project structure may vary depending on the current development version.

---

## 🔐 Privacy

Swanirbhar is designed with privacy-focused workflows in mind.

The application is intended to support **local and controlled environments**, making it suitable for scenarios where sensitive documents and project data should remain within the user's environment.

> The current demo release does not represent the complete production AI architecture.

---

## 🚀 Future Roadmap

Planned capabilities include:

- 🤖 Local AI model integration
- 🧠 Agentic AI workflows
- 📄 Advanced document understanding
- 🔍 Retrieval-Augmented Generation (RAG)
- 👁️ OCR and vision-based document analysis
- 💻 AI-powered coding assistance
- 🔒 Enhanced sandboxing and security
- 📊 Advanced monitoring and audit logs
- 🔌 Modular AI model routing
- 🏢 On-premise deployment for confidential workloads

---

## 📜 License

This project is currently being developed as part of the **Smart India Hackathon (SIH)** project and is subject to the project's applicable terms and conditions.

---

## 📬 Contact

For questions, feedback, or collaboration, please contact the development team through the GitHub repository.

---

## ⭐ Support the Project

If you find Swanirbhar interesting, consider giving the repository a ⭐ on GitHub and sharing your feedback.

**Built with ❤️ by Team TechTitans**
