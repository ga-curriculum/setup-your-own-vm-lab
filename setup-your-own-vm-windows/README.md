<h1>
  <span class="headline">Setup Your Own VM</span>
  <span class="subhead">Windows</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to create a new VM and install an operating system on it.

# Installing VirtualBox

1. Go to the [VirtualBox](https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html) website.

2. Choose the version that matches your computer's operating system (Windows, Mac, or Linux) and click on it to start the download.

3. Once the download is finished, double-click on the downloaded file to start the installation.

4. Follow the installation wizard, accepting the default settings unless you have a specific reason to change them.

5. When the installation is complete, launch VirtualBox.

## Reflection

- What version of VirtualBox did you install?
- Did you encounter any issues during the installation? If so, how did you resolve them?

# Creating Your First Virtual Machine

1. Create a new VM in VirtualBox. Name it (e.g., "Windows VM"), choose "Microsoft Windows" as the type, and select the appropriate version (e.g., "Windows 10 (64-bit)"). Click "Next".

2. Allocate at least 2048 MB (2 GB) of RAM to your VM. 4 GB or more is recommended for better performance. Click "Next".

3. Choose "Create a virtual hard disk now" and click "Create". Choose "VDI (VirtualBox Disk Image)" and click "Next".

4. Choose "Dynamically allocated" and click "Next".

5. Specify a location and size for your virtual hard disk. For a Windows VM, it's recommended to allocate at least 50 GB. Click "Create".

6. Your new VM should now appear in the VirtualBox Manager. Select it and click "Settings".

7. In the "System" section, go to the "Processor" tab and allocate at least 2 CPUs.

8. In the "Display" section, allocate the maximum amount of video memory (128 MB) and enable 3D acceleration.

9. Click "OK" to save your settings.

10. VirtualBox will ask you for a start-up disk. This is the ISO file that contains the operating system you want to install. Download an Microsoft Windows 10 ISO from the official [Microsoft website](https://www.microsoft.com/en-us/software-download/windows10ISO) and select it here.

11. The Windows installer should start automatically. Follow the on-screen instructions to complete the installation.

## Reflection

- What challenges did you face while creating your VM? How did you overcome them?
- How much RAM and hard disk space did you allocate to your VM? Why did you choose these amounts?
- What do you think would happen if you allocated too much RAM to your VM?

# Configuring Your Windows Virtual Machine

1. Start your Windows VM and wait for it to boot up.

2. Once you're at the Windows desktop, open the VirtualBox menu by clicking on the VirtualBox logo at the top of the VM window.

3. Go to "Devices" and then "Insert Guest Additions CD image". This will mount a virtual CD containing the VirtualBox Guest Additions, which are tools that improve the performance and usability of your VM.

4. Open File Explorer in your VM and navigate to the CD drive. Double-click on the "VBoxWindowsAdditions" executable to start the installation.

5. Follow the prompts to install the Guest Additions. This will require a restart of your VM.

6. After restarting, go back to the VirtualBox menu and select "Devices" > "Shared Clipboard" > "Bidirectional". This will allow you to copy and paste between your host and your VM.

7. Next, let's allocate more video memory to improve graphical performance. Shut down your VM, then in the VirtualBox Manager, select your VM and click "Settings".

8. In the "Display" section, allocate the maximum amount of video memory (128 MB) and enable 3D acceleration. Click "OK".

9. Start your VM again. You should notice improved graphics performance, especially if you're running graphically intensive applications.

## Reflection

- What settings did you change and why?
- How did your VM perform before and after changing the settings?
- What other settings do you think could be important for optimizing a VM's performance?
