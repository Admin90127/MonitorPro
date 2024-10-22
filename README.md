# MonitorPro

**MonitorPro** is a powerful and user-friendly system monitoring tool developed in Java, designed to provide comprehensive insights into your computer's processes and system performance. Inspired by tools like Process Hacker, MonitorPro offers detailed information about running processes, resource usage, and system services, enabling users to monitor and manage their systems effectively.

## Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Contact](#contact)

## Features

- **Process Management**
  - View a comprehensive list of all running processes.
  - Terminate, suspend, resume, and change the priority of processes.
  - Detailed information about each process, including CPU and memory usage.

- **Resource Monitoring**
  - Real-time monitoring of CPU, memory, disk, and network usage.
  - Visual graphs and charts to track resource consumption over time.

- **Service Management**
  - View and manage system services.
  - Start, stop, and configure services directly from the application.

- **Search and Filter**
  - Quickly find processes or services by name, PID, or other criteria.
  - Advanced filtering options to narrow down the list of processes.

- **Notifications and Alerts**
  - Receive alerts for critical events such as high CPU usage or unexpected process termination.

- **Logging and History**
  - Maintain logs of system events and user actions for auditing and troubleshooting.

- **User-Friendly Interface**
  - Intuitive GUI built with JavaFX for easy navigation and operation.
  - Customizable themes and settings to suit user preferences.

## Screenshots

![Main Interface](screenshots/main_interface.png)
*Main interface displaying running processes and resource usage.*

![Process Details](screenshots/process_details.png)
*Detailed view of a selected process.*

![Resource Graphs](screenshots/resource_graphs.png)
*Real-time graphs showing CPU and memory usage.*

## Getting Started

Follow these instructions to set up and run MonitorPro on your local machine.

### Prerequisites

- **Java Development Kit (JDK) 11 or higher**
  - Ensure Java is installed by running `java -version` in your terminal or command prompt.
  - Download JDK from [Oracle](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html) or [OpenJDK](https://openjdk.java.net/install/).

- **Maven or Gradle (Optional)**
  - If you plan to build the project from source, ensure you have Maven or Gradle installed.
  - Download Maven from [here](https://maven.apache.org/download.cgi) or Gradle from [here](https://gradle.org/install/).

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Admin90127/MonitorPro.git
   cd MonitorPro
