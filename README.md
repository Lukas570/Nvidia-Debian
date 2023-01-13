# Automatic Download and Installation of the Nvidia-Unix-Driver
Fetches the current Version of the Nvidia-Driver (for Debian) and downloads it

# Why?
This is for everyone owning an Nvidia-Graphics card and is using Debian or any other OS based on Debian.

# How?
Download the scripts and make them executable:

cd Nvidia-Debian

chmod +x *

# Downloading The Driver

./Download_Nvidia

WARNING! After executing the script, which downloads the current driver it will immediatly reboot in Runlevel 3. You won't have any graphics driver so your screen resolution will be very low and its only Terminal-based. Login with your username and password.

# Installation Of The Driver

Now being in Runlevel 3 and logged in get into the "Nvidia-Debian" folder and execute:
./Install_Nvidia

After the installation your system will reboot automatically into your normal Desktop-Environment with the new Nvidia-Driver being installed. CHeck the installed version with "nvidia-smi"
