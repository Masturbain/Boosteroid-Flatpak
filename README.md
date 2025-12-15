# Boosteroid Flatpak

This flatpak is based on the official Linux "portable" executable from Boosteroid.
<br>
<br>
<br>
A precompiled Flatpak is available from download in the releases.
<br>
<br>
<br>
You can also compile it yourself from the files given in the repo by following these instructions : 

- Install required dependencies : flatpak, flatpak builder
- Clone the repository on your machine : git clone https://github.com/Masturbain/Boosteroid-Flatpak.git/
- Download Boosteroid Linux "portable" install script : wget https://boosteroid.com/linux/installer/BoosteroidInstall.sh
- Run the script
- It should create a folder with an executable inside and an svg icon
- Paste the executable and icon in the cloned repository folder
- Then to install to current user run : flatpak-builder --user --install --force-clean build-dir com.boosteroid.Client.yml
