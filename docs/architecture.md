# Architecture

## Main Idea
The Raspberry Pi 4 acts as the main backup server. It manages storage, file access, and any web or network-based sharing features. The ESP32-C3 is reserved for future support functions such as hardware control, status indication, or user interface features.

## System Roles
- Raspberry Pi 4: storage, server logic, file sharing
- ESP32-C3: future control and expansion
- Mac/iPhone: devices used to send files to the backup server

## Design Approach
This project is being developed in stages. The first stage focuses on getting the Raspberry Pi working as a simple file backup system before adding extra hardware features.
<img width="1060" height="388" alt="Draft idea (1)" src="https://github.com/user-attachments/assets/33885458-d4ed-4a37-9605-e5fec8733a6e" />
