# PiTVSwitch: Canon PTZ Camera Source Changer

PiTVSwitch is a project that uses the Orange Pi to display the video feed from a Canon PTZ camera on your TV. The camera streams its video via a hosted web server, and a tablet on the production site allows users to change the URL of the stream being viewed by the Orange Pi, effectively switching between camera feeds.

## Features

- **Remote Control**: Change camera sources from a tablet at the production site.
- **Stream Canon PTZ Camera**: Directly view the Canon PTZ camera feed on your TV (Works externally on WAN).
- **User-Friendly Interface**: Simple controls for changing the stream URL.
- **Customizable**: Modify the code to fit your specific needs.
- **Lightweight**: Efficient performance on Orange Pi hardware.

## Requirements

- **Hardware**:
  - Orange Pi board (any model above 4GB, GPU is recommended)
  - HDMI-connected TV
  - Canon PTZ camera with HTTP streaming capability (Note: This project worked with CR-N300,CR-N500)
  - Tablet connected on the same LAN for changing stream URLs

- **Software**:
  - Debian or Armbian OS installed on your Orange Pi
  - Chromuim (on the orangePi)

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/malsanabis/PiTVSwitch.git
   cd PiTVSwitch
