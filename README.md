WhatsApp x SecurityExpert
WhatsApp x SecurityExpert is a Python-based desktop application that provides a graphical interface to configure and run a background service for sending WhatsApp notifications from Security Expert systems.

The application allows operators to configure connection parameters, select event filters, and monitor the service output in real time through an integrated GUI.

⚙️ Key Features
Graphical interface built with CustomTkinter
WhatsApp number selection with international prefix support
Configuration of Security Expert connection parameters
Event filtering (alarm, access denied, access granted, tamper)
Real-time service output monitoring
Automatic generation of a config.json file
Launch and control of the WhatsAppServices.py background process
🏢 Project Purpose
The purpose of this project is to simplify the configuration and execution of a WhatsApp notification service for Security Expert environments, providing:

A user-friendly interface instead of manual configuration files
Centralized control of service parameters
Real-time visibility of service logs and status
🚀 Usage
Launch the GUI application on a Windows machine
Configure the WhatsApp number and API key
Set Security Expert connection parameters (IP, username, password, site ID)
Select which event types should trigger notifications
Click Start to launch the background service
Monitor the service output directly from the interface
⚠️ Requirements
Windows 10 or higher
Python 3.x
Required Python packages:
customtkinter
WhatsAppServices.py script available in the same directory
Internet connectivity for WhatsApp message delivery
📁 Configuration
When the service is started, the application generates a config.json file containing:

WhatsApp destination number
API key
Security Expert connection parameters
Selected event filters
This file is used by WhatsAppServices.py during execution.

💡 Notes
Intended for system integrators and security professionals
Designed to simplify WhatsApp notification setup for Security Expert systems
The GUI acts as a launcher and configuration manager for the service script


🔒 Private Repository
The repository is available at: [WhatsApp x SecurityExpert](https://github.com/SecurityExpert-Tools/WhatsApp-x-SecurityExpert-ITA-)

Access is restricted and requires prior authorization.
