# KumoMC

KumoMC is a lightweight performance-focused fork of Purpur, designed for local server hosting and small-scale environments.

## Overview

KumoMC builds on the stability and flexibility of Purpur while applying additional optimizations to improve performance on local machines. It is intended for personal use, testing, and small private servers.

## Goals

- Improve performance for low to mid-range hardware  
- Maintain compatibility with existing Purpur plugins  
- Provide a clean and minimal configuration setup  
- Keep behavior predictable and close to upstream Purpur  

## Features

- Optimized for local server performance  
- Reduced unnecessary overhead  
- Compatible with the Spigot / Paper / Purpur ecosystem  
- Simple and quick setup  

## Usage

1. Download the latest KumoMC jar  
2. Place it in your server directory  
3. Create a file named `start.bat`  
4. Add the following content:

```bat
@echo off
cd /d "your_directory"
start playit.exe
java -Xmx8G -jar kumoMC.jar nogui
pause
```

5. Replace "your_directory" with your actual server path
6. Run start.bat to start the server

## Notes
- -Xmx8G means 8 GB RAM allocation
- You can change it to match your system (e.g., 4G, 16G)
- Ensure playit.exe (or simiar port forwarding)

## Disclaimer

KumoMC is intended for local and personal use only. It is not tested for large-scale or production environments.

## Credits

Based on Purpur
Built on top of Paper and Spigot

---
