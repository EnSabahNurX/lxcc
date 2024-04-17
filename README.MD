# LXDE Control Center

## Overview

LXDE Control Center is a graphical user interface (GUI) application built with Python and Gtk. It provides a centralized location for accessing various system configuration and management tools commonly used in LXDE (Lightweight X11 Desktop Environment).

## Features

- Access to essential system configuration tools.
- User-friendly interface with icon-based navigation.
- Easy integration with LXDE environment.

## Prerequisites

- Python 3
- Gtk 3.0

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/EnSabahNurX/lxcc

2. **Change directory to the project folder:**

   ```bash
   cd lxcc
3. **Install dependencies:**
   ```bash
   sudo apt-get install python3-gi
4. **Run the application:**

   ```bash
   ./usr/bin/lxcc
### Alternative installation
1. **Build a dpkg file to install it. Do this command below outside of the folder containg the cloned data from github:**
   ```bash
   dpkg --build lxcc
1. **Install using dpkg:**
   ```bash
   dpkg -i lxcc.deb
   sudo apt install -f
## Usage
- Click on the icons to launch corresponding system configuration tools.
- Some actions may require superuser privileges and will prompt for authentication.
## Licence
This project is licensed under the MIT License
## Acknowledgements
Special thanks to the developers of the LXDE project and the Gtk library.