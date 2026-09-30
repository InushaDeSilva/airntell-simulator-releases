# Airntell Flight Simulator

Download builds from [Releases](https://github.com/InushaDeSilva/airntell-simulator-releases/releases). This repository hosts tester downloads; the Unity source is private.

**Windows:** run the x64 or ARM64 `Setup` installer. It creates a direct game shortcut.

**macOS:** download the Apple Silicon or Intel ZIP, extract it, and open the app. These tester builds are unsigned and not notarized.

**Linux:** extract the x64 ZIP and run `AirntellFlightSimulator.x86_64`. If your archive tool strips permissions, use `chmod +x AirntellFlightSimulator.x86_64`.

The game opens its own main menu. Enter the open-pit mine from there. Optional updates download inside the game and install after it closes. No separate launcher is required. The `.partNNN` assets and platform JSON files are used by the in-game updater; download the installer or full ZIP for a first install.

In **Simulate → Underbody sensors**, start the payload to publish synthetic LiDAR, camera, IMU, GNSS and frame transforms. The game displays its LAN/Tailscale Foxglove addresses. Native ROS 2 uses domain 42 by default, with interface and peer settings for unicast discovery. Windows provides a firewall setup button requiring administrator approval; other systems may need OS firewall permission.

This is a geometry and transport prototype. Sensor noise, drift and the Avia firing law are not hardware-calibrated, and full-workload rates are not guaranteed. Read each release's validation notes before relying on a platform or network configuration. It is not connected to a real aircraft.

Releases are published manually, only when requested.