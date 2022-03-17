# How to install napari as bundled app

```{note}
If your mainly use napari as a standalone GUI app, this method allows you to install napari as an app without worrying about Python environment. However, certain plugins may not be supported.
```

```{note}
If you want to use napari from Python to programmatically interact with the app, please follow the [Python package installation guide](installtion_python.md). It is the best way to install napari and make full use of all its features. 
```

```{note} 
If you want to contribute code back into napari, please follow the [development installation instructions in the contributing guide](https://napari.org/developers/contributing.html).
```

## Prerequisites

This installation method does not have any prerequisites. 

## Install as a bundled app

napari can be installed as a bundled app on
MacOS, Windows, and Linux with a simple one click download and installation process. 

[TO DO]: links to each platform's bundle

To access earlier versions of napari, you can visit our [release
page](https://github.com/napari/napari/releases) and scroll to the release you
are interested in and expand the `assets` tab.

[TO DO]: update the following sections
### Installing the MacOS bundle

Once you have downloaded the MacOS bundle zip you will have a zip file with a
name like `napari-0.3.7-macOS.zip`. After unzipping you will have a file with a
name like `napari-0.3.7.dmg`. Double clicking the `dmg` will open a new finder
window giving you the option to install napari into your `Applications` folder
by dragging the `napari` icon onto the `Applications` icon.

![image: MacOS install to
Applications](../assets/tutorials/installation/bundle_install.png)

After you drag the `napari` icon onto the `Applications` icon napari will be
installed in your Applications folder and available for opening by double
clicking on it.

![image: MacOS Applications folder with
napari](../assets/tutorials/installation/bundle_applications_folder.png)

The first time you try and open napari you will get the "unverified developer
warning" that appears below:

![image: MacOS developer
warning](../assets/tutorials/installation/bundle_dev_warning.png)

Don't be alarmed, this is because the napari team has not yet obtained a
developer certificate from Apple, but we will be doing this promptly. It is safe
to click "Cancel". To get napari to open you must enter "Systems Preferences"
and click the "Security & Privacy" icon, circled in red below:

![image: MacOS Security & Privacy
settings](../assets/tutorials/installation/bundle_security_privacy.png)

Once inside the "Security & Privacy" tab, you should see a message about napari
being blocked and an "Open Anyway" button, circled in red below:

![image: MacOS "Open Anyway"
settings](../assets/tutorials/installation/bundle_open_anyway.png)

After clicking this button you'll get one final warning about napari not being
verified, but now you'll have an "Open" button, as seen below:

![image: MacOS open bundle dialog
box](../assets/tutorials/installation/bundle_open.png)

After clicking "Open", the viewer should appear. Don't worry, you only have to
go through this process once when you install a new bundle.

### Installing the Windows bundle

Once you have downloaded the Windows bundle zip you will have a zip file with a
name like `napari-0.3.7-Windows.zip`. Unzip the bundle (you may like to use a
tool like [7-zip](https://www.7-zip.org/) for this) and double click on msi
file, eg: `napari-0.3.7.msi`

The napari setup wizard will then open. Click "Next" to begin the installation.

![image: Windows napari setup
wizard](../assets/tutorials/installation/windows_bundle_installer_start.png)

![image: Windows napari setup wizard in
progress](../assets/tutorials/installation/windows_bundle_installer_progress.png)

After the setup wizard has installed napari, click "Finish" to exit.

![image: Windows napari setup wizard
finished](../assets/tutorials/installation/windows_bundle_installer_finish.png)

When you launch the bundled napari app on Windows, first you'll see an empty
command terminal appear (do not close this window - you can ignore it). The
command terminal will be followed by a napari splash screen, and then the main
napari user interface window will appear a few seconds later. Note that errors
which might occur during your napari session will appear on the command terminal - 
so if something is not working, it might pay to take a look at the terminal!

![image: Windows command terminal on napari
launch](../assets/tutorials/installation/windows_bundle_command_terminal.png)

You can launch napari from the Windows start menu.

![image: Windows launch napari from start
menu](../assets/tutorials/installation/windows_launch_napari.png)

The very first time you launch napari the startup time will be fairly slow, but
after that you will find that napari launches more quickly.

### Installing the Linux bundle

(Guide coming soon... In the meantime, if you try it and encounter issues, see
below for how to contact us.)
<!-- #endregion -->

## Launching napari

[TO DO]