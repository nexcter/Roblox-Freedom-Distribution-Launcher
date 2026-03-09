# Roblox Freedom Distribution Launcher (RFD:L)
![RFD:L Banner](images/RFDL_BANNER.png)
A graphical launcher for Windows81's Roblox Freedom Distribution, built using the Godot Engine.

RFD:L provides an easy to use interface that communicates with the RFD command-line program, allowing users to host and join servers without manually using the terminal.

# Requirements
- Windows operating system
- 2 GB RAM
- Dual-core processor
- OpenGL 3.3 or OpelGL ES 3.0 compatible graphics hardware

# Installation
- Download the latest release of [Roblox-Freedom-Distribution](https://github.com/Windows81/Roblox-Freedom-Distribution).
- Extract RFD to a folder.
- Download the latest RFD:L release from this repository.
- Place the launcher anywhere you want and run the program.

# Hosting a Server
- To host a server using RFD:L, you must obtain a place which has a ```GameConfig``` file.
- Example places and their ```GameConfig```s can be found [here](https://github.com/Windows81/Roblox-Freedom-Distribution-Examples/tree/0306621b10ad9e3074db00b599a14affe96817d9)
- Open port 2005 on both TCP and UDP.
- Start the server through the launcher, making sure to provide the path to the ```GameConfig``` file.
- Give players your public IP address to allow them to join
- The Roblox client version used will automatically match the ```roblox_version``` specified in the GameConfig file.

# Joining a Server
- To join a server using RFD:L, you must obtain the host's IP address.
- Enter the address in the launcher.
- Join the game.
- The launcher will automatically select the correct Roblox client version based on the server's ```GameConfig```.

# Screenshots
![RFD:L Login page](images/S1.png)
![RFD:L Home page](images/S2.png)
![RFD:L Host page](images/S3.png)
![RFD:L Roblox High](images/S4.png)

# Disclaimer
- RFD:L is not affiliated with or endorsed by Windows81 or Roblox.
- RFDL is simply a community-made launcher designed to make using the Roblox Freedom Distribution easier.

# Credits
- Windows81 - Roblox Freedom Distribution
- Godot Engine distru
