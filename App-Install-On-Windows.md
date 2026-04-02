# 1. Introduction

This document describes how to install the noBLE Companion app on a Windows PC.  This app is used to configure and control a noBLE device over Bluetooth Low Energy (BLE).

The app is written in Python, so it can run on any platform that has a Python 3 runtime environment available. If your Windows PC has a Python 3 runtime environment already installed, you can skip the following section and jump to section #3.

# 2. Install Python

Windows does not come with Python preinstalled, so unless you have already installed it for other purposes, you will need to install it now.  The good news is that Python is free and easy to install.

On Windows you can install Python in two different ways:

* Directly from the [MS Store](https://apps.microsoft.com/detail/9nq7512cxl7t?ocid=webpdpshare)
* Downloading the installer for the latest stable release from the official Python web site [python.org](https://www.python.org/downloads/windows)

In this tutorial we will install Python using the Microsoft Store app.

Open the Microsoft Store app and search for “python install”.  You should get this:

<br>

![noBLE](./assets/App-Install-On-Windows/SS-01.png)

<br>

Press the blue Get button and wait until the software is downloaded and installed.  When the process is complete, the Get button should change to Open:

<br>

![noBLE](./assets/App-Install-On-Windows/SS-02.png)

<br>

When you click the Open button a Command Prompt window will automatically open up, to ask you a few questions about some post-install options.  See the screenshots below:

<br>

![noBLE](./assets/App-Install-On-Windows/SS-03.png)

<br>

![noBLE](./assets/App-Install-On-Windows/SS-04.png)

<br>

![noBLE](./assets/App-Install-On-Windows/SS-05.png)

<br>

To check that the installation was successful, open a PowerShell terminal and run the command:

```
python --version
```

which simply prints the version number and exits. In this example the version installed was 3.14.3:

<br>

![noBLE](./assets/App-Install-On-Windows/SS-06.png)

<br>

> [!TIP]
> While this step is not strictly necessary, at this point you may want to run the following command, to update Python's installer "pip" to the latest version:

```
python -m pip install --upgrade pip
```

<br>

