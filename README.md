# <h1 align="center">Parrot Linux Termux</h1>
<p align="center"> Parrot Security (ParrotOS, Parrot) is a Free and Open source GNU/Linux distribution based on Debian Stable designed for security experts, developers and privacy aware people. It includes a full portable arsenal for IT security and digital forensics operations.</p>

<br>

# Requirements
* [Termux](https://github.com/xiv3r/Kali-Linux-Termux/releases/download/Apps/Termux_v0.119.1.apk)


## Installations


1. Update & Upgrade Termux:

       apt update && pkg upgrade -y
   
3. Install wget:

       pkg install wget proot git curl -y
   
4. Download script:

       git clone https://github.com/xiv3r/Parrot-Linux-Termux.git

7. Go to script folder:

       cd Parrot-Linux-Termux
  
10. Give execution permission:

        chmod +x install.sh
    
11. Install:

        bash install.sh -y

12. Run:

        cd Parrot-Linux-Termux
         
        ./start.sh
