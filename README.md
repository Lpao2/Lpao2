# Hi, I'm Lucas Patrocínio 👋

Electronic Engineering student at the Federal University of Santa Catarina — UFSC, with experience in software development, automation, Linux infrastructure and embedded systems.

I enjoy building complete projects that connect software, hardware, APIs, automation and real-world problem solving.

Currently, I am improving my skills in application development, backend systems, DevOps and mobile development.

---

# Featured Projects

## 🎬 AutoShorts — Automated Video Processing Pipeline

AutoShorts is an automation project designed to process long-form content and generate short-form videos with reduced manual intervention.

The project automates different stages of the content production workflow, helping organize source files, process media and generate content suitable for short-video platforms.

### Main features

- Automated video processing workflow
- Organization of input and output files
- Content segmentation
- Media processing automation
- Execution monitoring
- Error handling
- Reduction of repetitive manual work

### Technologies

`Python` `Media Processing` `APIs` `Automation` `File Management`

### Main technical challenges

- Coordinating multiple processing steps
- Managing large media files
- Organizing generated content
- Handling failures during long-running operations
- Creating a repeatable automation pipeline

### Status

Functional prototype completed and continuously improved.

<!-- Add the repository link when ready -->
<!-- [View repository](https://github.com/Lpao2/autoshorts-pipeline) -->

---

## 🖥️ Autotech Server — Automated Linux Media Server Platform

Autotech Server is an automated deployment platform for a self-hosted Linux server.

The project installs and configures a complete Docker-based environment for media management, download automation, subtitle management and custom content-processing services.

The main goal was to transform a complex server installation into a more accessible and repeatable deployment process.

### Main components

- Jellyfin media server
- Sonarr series management
- Radarr movie management
- qBittorrent download client
- Jackett indexer integration
- Bazarr subtitle management
- Custom manga automation services
- Python APIs
- Automated installation scripts
- Linux system services
- Docker container orchestration

### Main features

- Automated Linux environment setup
- Docker and Docker Compose installation
- Container creation and configuration
- Persistent service configuration
- Automatic directory creation
- Storage organization between SSD and HDD
- API communication between multiple services
- Automated media download and import pipeline
- Custom Jellyfin interface modifications
- Manga download and library automation
- Installation through a prepared USB drive

### Architecture overview

```text
User Request
     │
     ▼
Custom Interface / API
     │
     ├── Sonarr ──► Jackett ──► qBittorrent
     │
     ├── Radarr ──► Jackett ──► qBittorrent
     │
     └── Manga Automation Service
                          │
                          ▼
                     Media Storage
                          │
                          ▼
                       Jellyfin
```

### Technologies

`Linux` `Ubuntu Server` `Docker` `Docker Compose` `Python` `Flask`

`Shell Script` `PowerShell` `JavaScript` `REST APIs` `Systemd`

### Main technical challenges

- Managing Docker volumes and permissions
- Integrating multiple independent services
- Automating installation and configuration
- Maintaining persistent data between deployments
- Coordinating downloads, imports and media organization
- Creating communication between Python services and third-party APIs
- Managing Linux services and scheduled tasks
- Designing a plug-and-play installation process

### Status

Linux deployment completed and functional.

The Windows installation workflow was also explored using WSL, but hardware virtualization and Docker compatibility limitations made Linux the primary supported platform.

<!-- Add the repository or documentation link when ready -->
<!-- [View project documentation](https://github.com/Lpao2/autotech-server-platform) -->

---

## 💬 Desktop Messaging Chatbot

The Desktop Messaging Chatbot is a Windows desktop application created to manage automated conversations between authorized messaging accounts.

The project combines browser automation, session management, configurable conversation workflows and a graphical desktop interface.

It was also packaged as a standalone Windows application, allowing users to run it without manually installing or configuring the complete development environment.

### Main features

- Desktop graphical interface
- Browser automation
- Messaging session management
- Configurable conversation workflows
- Start and stop controls
- Multiple account support
- Automatic browser profile handling
- Execution feedback and status messages
- Windows application packaging
- Automated dependency installation

### Technologies

`Python` `Playwright` `Desktop GUI` `Browser Automation`

`PyInstaller` `Batch Script` `Windows`

### Main technical challenges

- Managing multiple browser sessions
- Preserving authenticated sessions
- Coordinating automated conversations
- Preventing conflicting executions
- Creating a simple interface for non-technical users
- Packaging the application for Windows
- Handling Python and browser dependencies automatically

### Status

Functional desktop application completed.

<!-- Add the repository link after removing credentials and private configuration -->
<!-- [View repository](https://github.com/Lpao2/desktop-messaging-chatbot) -->

---

## 📚 BookRats — Social Study Planning App

BookRats is a mobile application designed to combine academic planning, study tracking and social motivation.

The application allows students to organize their subjects, record study sessions, create groups and follow the academic progress of their friends.

The concept is based on making studying more collaborative, visible and motivating.

### Main concept

```text
Plan the semester
        │
        ▼
Create subjects and goals
        │
        ▼
Start a study session
        │
        ▼
Record progress
        │
        ▼
Share with friends
        │
        ▼
Receive support and motivation
```

### Planned features

- User accounts and profiles
- Semester planning
- Subject management
- Study timer
- Manual study session registration
- Social activity feed
- Groups and invitations
- Weekly study goals
- Group rankings
- Study streaks
- Reactions and comments
- Exam and assignment tracking
- Shared academic challenges
- Progress statistics
- Optional photo sharing

### Example study post

```text
Lucas studied for 1h 32min

Subject: Calculus IV
Topic: Laplace Transform
Goal: Complete exercise list 3
Result: 8 of 10 exercises completed

“Still reviewing convolution.”

🔥 5 reactions
💬 3 comments
```

### Planned technologies

`Flutter` `Dart` `Supabase` `PostgreSQL`

`Android` `REST APIs` `Cloud Storage`

### Main goals

- Help students maintain study consistency
- Make academic planning easier
- Encourage collaboration between friends
- Allow students to understand what their friends are studying
- Create motivation through groups and challenges
- Combine personal organization with social accountability

### Current development stage

Initial planning and interface development.

The first version will focus on:

- Feed
- Semester
- Study session
- Groups
- Profile

<!-- Add the repository link when the project is created -->
<!-- [View repository](https://github.com/Lpao2/bookrats) -->

---

# Technical Areas

## Software Development

- Python applications
- Desktop applications
- Mobile application development
- REST API integration
- Browser automation
- File and media processing

## Infrastructure and DevOps

- Linux server administration
- Docker
- Docker Compose
- Systemd services
- Shell scripting
- Automated deployment
- Self-hosted infrastructure

## Embedded Systems

- ESP32
- ESP-IDF
- FreeRTOS
- GPIO
- UART
- I2C
- Task and queue management
- Electronic system integration

---

# Technologies

### Programming languages

`Python` `C` `C++` `JavaScript` `Shell` `PowerShell`

Currently learning:

`Dart` `Flutter`

### Infrastructure

`Linux` `Ubuntu Server` `Docker` `Docker Compose` `Git` `GitHub`

### Development

`Playwright` `Flask` `REST APIs` `PyInstaller`

### Embedded systems

`ESP32` `ESP-IDF` `FreeRTOS` `UART` `I2C` `GPIO`

### Databases and backend

`SQLite` `PostgreSQL` `Supabase`

---

# Current Focus

- Developing the first version of BookRats
- Improving project documentation
- Building a professional software and engineering portfolio
- Expanding my knowledge of mobile development
- Improving backend and cloud development skills
- Creating projects that combine electronics and software

---

# Contact

- **Email:** lucas.patrocinio3003@gmail.com
- **GitHub:** [github.com/Lpao2](https://github.com/Lpao2)
- **LinkedIn:** https://www.linkedin.com/in/lucas-patrocinio-300300/

---

<p align="center">
  Building practical solutions through software, electronics and automation.
</p>
