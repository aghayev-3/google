# Installing, Updating, and Removing Software in Windows

## Verifying initial setup on Windows

* To verify whether or not a program is installed in Windows, click the **Search** icon in the bottom-left of the taskbar, and start typing **Apps & Features** to search. 
* Then, click **Apps & Features**. 
* You can also **right-click** on the **Start** icon, and click on **Apps & Features** at the top of the menu.
* This will bring up the **Apps & Features**, which shows a list of every program that's installed on the computer.
* By looking at this applet, you can see that **Mozilla** software isn't present, so we know that it's not currently installed. 
* Similarly, we can see that **VLC** and **GIMP** are both already installed, so we're ready to proceed. 
* Note that the installed version of **VLC** is 3.0.8; this isn't the most recent version, so we'll update it later on in this lab.

## Maintaining software on Windows

* Now that we know that the **Windows** instance is properly configured (i.e. we have verified that **Mozilla** is not installed, but **VLC** and **GIMP** are both already installed), you can move on to the hands-on part of the lab; maintaining the software.

### Installing Mozilla Firefox

* First, you'll install the **Mozilla Firefox** browser in the **Windows** instance. To install **Firefox**, you need to download the **Windows installer** from the **Firefox website**. To do this, double-click the **Google Chrome** icon on the left side of the desktop screen, and navigate to this url:
* `https://www.mozilla.org/en-US/firefox/new/`
* From this site, click the **Download** link to download the installer.
* Once the download finishes, click the installer icon in the top-right side of the browser window.
* This launches the installer, and starts the installation process. 
* Click **Yes** if **Windows** asks if you wish to install it, and the installer should open and begin.
* Click **Next** through any options that appear during the installation process. 
* Wait for this process to finish, and **Mozilla** will be installed. 
* A shortcut to **Firefox** will be added to the desktop, and you can double-click it to open your newly installed browser.

### Updating VLC Media Player

* We saw before that an old version of **VLC Media Player** is already installed on the **Windows VM** we're using. 
* This is an old version; we'll now learn how to update it in **Windows**. 
* First, you need to get an installer for the new version from **VLC's website**. 
* Open the link below to download the installer:
* `https://www.videolan.org/vlc/download-windows.html`
* Click on drop-down menu beside **Download VLC** and select **Installer for 64bit version** and wait for the installer to finish downloading.
* Once done, click on the installer to open it (like you did for **Firefox**).
* Once the installer opens, choose whichever language you're comfortable with, then click **Next** to begin the process.
* Choose **Upgrade VLC using previous settings(recommended)** and then click **Next**. A progress bar appears and the upgrade process begins.
* When the process is finished, a confirmation message will appear. Uncheck the option to run **VLC**, then click **Finish** to close the installer.
* Reopen the **Apps & Features** window and you'll see that **VLC** is now at the latest version.

### Uninstalling GIMP

* Uninstalling a program on Windows is super simple. Navigate back to **Apps & Features** and **right click** on the program you want to remove (i.e. **GIMP**). A single-item dropdown menu should appear.
* Click on the **Uninstall** option in the dropdown. 
* A confirmation menu will appear, asking if you're sure you want to proceed. 
* Click **Yes** and the uninstallation process will begin.
* When this process finishes, a confirmation menu will appear. 
* Clicking **OK** on that menu will close it, and **GIMP** should no longer appear on the list of installed programs.
* This completes the uninstallation process.
