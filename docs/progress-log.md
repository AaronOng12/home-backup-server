# Progress Log

## Entry 1 (04/01/2026)
- Selected project concept
- Defined main use case: backing up photos, short videos, and documents
- Chose Vilros Raspberry Pi 4 kit as the main platform
- Chose ESP32-C3 as a future expansion microcontroller
- Created GitHub repository

## Next Entry Ideas
- Raspberry Pi OS setup started
- Initial file-sharing method selected

## Entry 2 (04/02/2026)
# Day 1 - Raspberry Pi Initial Setup

## What I did
- Installed heatsinks and assembled the Raspberry Pi 4
- Booted Raspberry Pi OS
- Completed first-time setup
- Connected to network
- Updated the system
- Enabled SSH
- Logged in remotely from my Mac

## Result
The Raspberry Pi is now set up and ready for the next stage of the home server project.

## Next Step
Create the project directory structure and start configuring basic server functionality.

## Entry 3 (04/03/2026)
# Day 2 - Real Home Server Setup

## What I did
- Set up Samba on the Raspberry Pi so it could function as a network file server.
- Created and configured a custom shared folder, updated the smb.conf file, fixed the share visibility issue
- Connected to it from Mac through Finder using SMB.

## Result
The Raspberry Pi successfully became accessible as a shared network drive, and I was able to open the folder from my Mac and confirm that the connection worked.

## Next Step
Test file transfers between the Mac and Raspberry Pi, organize the shared storage into useful folders, and continue building the server into a more practical home backup/storage system.
