# Linux Dynamic Wallpapers

<img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Logo.png" width="128">

<b>[Dynamic wallpapers like MacOS for Linux](https://www.gnome-look.org/p/1499429/)</b>

   * Tested on Manjaro Gnome 20.2.1

<b>INSTALLATION:</b>

1. download package:

   if you already installed this package, remove previous package before updating
   
       sudo rm -r /usr/share/backgrounds/Dynamic_Wallpapers
       
   clone git repository:
   
       cd ~
       git clone https://github.com/saint-13/Linux_Dynamic_Wallpapers.git
       cd Linux_Dynamic_Wallpapers

2. install it with command : 
   
       sudo bash ./install.sh

3. change your wallpaper from: settings > Backgrounds

4. that's it. enjoy!

<b>SCREENSHOTS:</b>

<table>
  <tr>
    <th>Surface</th>
    <th>SurfaceBreeze</th>
    <th>BigSur</th>
    <th>BigSurV2</th>
    <th>Catalina</th>
  </tr>
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Surface.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/SurfaceBreeze.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/BigSur.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/BigSurV2.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Catalina.gif" width="128">
    </td>
  </tr>
  <tr>
    <th>Mojave</th>
    <th>MojaveV2</th>
    <th>Minimal Mojave</th>
    <th>ZorinMountain</th>
    <th>ZorinMountainFog</th>
  </tr>
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Mojave.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/MojaveV2.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Minimal-Mojave.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/ZorinMountain.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/ZorinMountainFog.gif" width="128">
    </td>
  </tr>
  <tr>
    <th>ZorinBlur</th>
    <th>Coast</th>
    <th>Desert</th>
    <th>Material</th>
    <th>RockyMountain</th>
  </tr>
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/ZorinBlur.gif" width="128">
    </td>
    <td>
       <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Coast.gif" width="128">
    </td>
    <td>
       <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Desert.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Material.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/RockyMountain.gif" width="128">
    </td>
  </tr>
  <tr>
    <th>WhiteLighthouse</th>
    <th>WeYamle</th>
    <th>SnowMountain</th>
    <th>Sunset</th>
    <th>ViktorForgacs</th>
  </tr>
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/WhiteLighthouse.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/EOS-WeYamle.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/EOS-SnowCappedMountain.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/EOS-Sunset.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/EOS-ViktorForgacs.gif" width="128">
    </td>
  </tr>
  <tr>
    <th>MagicLake</th>
    <th>UbuntuMinimal</th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
  <tr>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/MagicLake.gif" width="128">
    </td>
    <td>
      <img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/UbuntuMinimal.gif" width="128">
    </td>
    <td>
    </td>
    <td>
    </td>
    <td>
    </td>
  </tr>
</table>



old method for instasllation : -----------------------------------------

1. download package from www.gnome-look.org/p/1499429/:
   
      *  extrate package
      
      *  go to extracted folder, right click and open in terminal

2  move Dynamic_Wallpapers folder to /usr/share/backgrounds/

       sudo mv Dynamic_Wallpapers /usr/share/backgrounds/
       cd ~
       sudo rm -r Linux_Dynamic_Wallpapers

3. install gnome-tweak-tool.

    Arch:

       sudo pacman -S gnome-tweaks

    Ubuntu:

       sudo apt install gnome-tweaks

4. open gnome tweaks and select xml file. 

    e.g: select : /usr/share/backgrounds/Dynamic_Wallpapers/Mojave.xml
    
    Warning: if wallpaper does not show properly, you need to change all files and folder's permission in /usr/share/backgrounds/Dynamic_Wallpapers from root to your username

<img src="https://raw.githubusercontent.com/saint-13/Linux_Dynamic_Wallpapers/main/Screenshots/Screenshot%20from%202021-03-30%2019-45-07.png" width="512">

5. (optional) : you can install [Night Theme Switcher](https://extensions.gnome.org/extension/2236/night-theme-switcher/) extension for gnome shell to Automatically toggle your light and dark theme.

6. enjoy!
