# Airntell Mine Simulator — tester downloads

Desktop preview of the open-pit mine environment with moving workers and machinery, inspection cameras, and local M300 RTK / Sentinel drone views.

This repository contains downloads only. The development repository is private.

## Install and update

Download the launcher ZIP for your operating system from [Releases](https://github.com/InushaDeSilva/airntell-simulator-releases/releases). Extract the entire folder and open AirntellMineLauncher. Keep the accompanying libraries beside the launcher.

Choose **Download and install** in the launcher. It downloads the mine automatically; you do not need to join the large `.part` files yourself. Keep several gigabytes of free space for the download, installation and previous version.

Updates are optional. The launcher and simulator can check for new versions; close the simulator when you are ready to install. **Previous version** returns to the retained installation. Your screenshots and settings remain separate from application updates. If you are offline, you can start an already installed version.

The bootstrap launcher itself is replaced manually when a new launcher ZIP is released. Platform availability and testing status are stated in each release. Packages are unsigned unless that release explicitly says otherwise.

## Controls

- **Explore:** hold right mouse for look/movement; WASD, Q/E height, Shift fast, Ctrl precise.
- **1–6:** saved inspection views. **Space:** pause/resume. **R:** reset. **Tab:** hide the panel. **F12:** screenshot with pose/settings metadata.
- **Simulate:** choose the M300 RTK or Sentinel, local manual or replay pose, and payload or chase camera.
- **Manual preview:** WASD movement, Q/E height, left/right arrows yaw, up/down arrows gimbal.

This preview has no live DJI connection or flight-control authority. Manual controls move the local visual model only. Aircraft telemetry integration and calibrated sensors are later work. The Sentinel model's physical scale is provisional.

Visual quality is the priority; demanding graphics profiles need a capable GPU. Use the available graphics presets for your device. Windows, macOS and Linux are the intended desktop targets. There is no mobile version.
