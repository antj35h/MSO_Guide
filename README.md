> Piracy is our only option. ~ Emma Thompson

**Welcome to the high seas 🏴‍☠️, here is my guide on how to install and activate MS Office.**

If you already have Office installed → [here](#installed-office)

If you don't → [here](#step-1---configuring-installation)

---

# Step 1 - Configuring Installation

To configure installation, you need to download...a configuration file.

If you want to do it from scratch, go here → **Office Customization Tool** - [here](https://www.microsoft.com/en-us/download/details.aspx?id=49117)

If you want a file made from default setting from your Windows OS, download this file [here](assets/OfficeConfig.xml)

If you do not want to do this step and prefer an easier way → [here](#have-not-installed-office)

# Step 2 - Installation

Now that you have your config file, let's use that to install Office.

1. For convenience sake, rename the config file to `OfficeConfig.xml`.
2. Move this file to a new folder on the desktop, name the folder anything, preferably `Office Install`.
3. Download the **Office Deployment Tool** [here](https://www.microsoft.com/en-us/download/details.aspx?id=49117).
4. Standard Procedures: Open, YES to UAC prompt, accept the EULA, select the folder you made on desktop.
5. Once the extraction is done, open the folder.
6. Right-click and **Open in Terminal***
7. In the terminal, paste - `.\setup.exe /configure OfficeConfig.xml`, and ENTER.
8. Again, YES to UAC prompt, and wait for installation to get over with.
9. **Restart** your device when installation is done.


> [!NOTE]
> **Open in Terminal** option not there
> 
> You may be using Windows 10, or just don't have that option, then:
> 1. Open the folder
> 2. ALT+D or CTRL+L
> 3. Type in `powershell` and ENTER

> [!WARNING] 
> **Stay Online!**
> 
> Do not go offline or shut your device down until the installation finishes.

# Step 3 - MAS - Microsoft Activation Scripts

Check out MAS - [here](https://massgrave.dev/index.html)

## Have not installed Office

If you choose to not perform [Step 1](#step-1---configuring-installation) & [Step 2](#step-2---installation), then:

1. Right-click on the Windows start menu and select **PowerShell** or **Terminal**.
2. Copy and paste the code `irm https://massgrave.dev/get | iex` and press ENTER.
3. YES to UAC prompt.
4. Press `7` and then `4` - to download Office,
5. or go [here](https://massgrave.dev/genuine-installation-media.html).

Once you got your Office setup files, run it and wait for installation to get over with. **Restart** your device when installation is done.

> [!WARNING] 
> **Stay Online!**
> 
> Do not go offline or shut your device down until the installation finishes.

## Installed Office

Now that you have installed Office successfully, follow:

1. Right-click on the Windows start menu and select **PowerShell** or **Terminal**.
2. Copy and paste the code `irm https://massgrave.dev/get | iex` and press ENTER.
3. YES to UAC prompt.
4. Press `2` and then `1` - to activate Office.
5. Follow the on-screen instructions based on the results, i.e., if the activation was successful or not.
6. Once the activation is successful, restart your device (optional, but recommended) and...

Office has been activated, to check - [here](#step-4---check-activation-status).

## Method - 2

The above steps require you to paste a code into **PowerShell**. This method is recommended and completely safe. If you choose to rather install with another method:

1. Download the master file from - [here](https://github.com/massgravel/Microsoft-Activation-Scripts/archive/refs/heads/master.zip)
2. Right-click on the downloaded zip file and extract
3. In the extracted folder, find the folder named `All-In-One-Version`
4. Run the file named `MAS_AIO.cmd`
5. YES to UAC prompt.
4. Press `2` and then `1` - to activate Office.
5. Follow the on-screen instructions based on the results, i.e., if the activation was successful or not.
6. Once the activation is successful, restart your device (optional, but recommended) and...

Office has been activated, to check - [here](#step-4---check-activation-status).

# Step 4 - Check Activation status

1. Right-click on the Windows start menu and select **PowerShell** or **Terminal**.
2. Copy and paste the code `irm https://massgrave.dev/get | iex` and press ENTER.
3. YES to UAC prompt.
4. Press `5`.

OR

1. Open Word, Excel, or PowerPoint.
2. Go to Account and on the right-hand side you should see the message *"Product Activated"*.

# Step 5

**Your Office should be ACTIVATED by this step. Congrats!**

If in case your Office gets de-activated in the future, re-do [these steps](#installed-office).

---

# Sources

1. Rentry Office Guide - [here](https://rentry.org/office-guide)
2. MAS - [here](https://massgrave.dev/index.html)
3. MAS GitHub - [here](https://github.com/massgravel/Microsoft-Activation-Scripts/)
4. Open PowerShell in a Folder - [here](https://adamtheautomator.com/windows-open-powershell-in-a-folder/)
