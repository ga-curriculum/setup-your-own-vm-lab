<h1>
  <span class="headline">Setup Your Own VM</span>
  <span class="subhead">Ubuntu</span>
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

1. In VirtualBox, click on the "New" button to start creating a new VM.

2. Give your VM a name and choose the type of operating system you want to install. For this exercise, let's choose "Linux" and "Ubuntu x64". Click "Next".

3. Choose how much memory (RAM) to allocate to your VM. As a rule of thumb, don't exceed 50% of your computer's total RAM. 2048 MB (2 GB) is a good starting point. Click "Next".

4. Choose "Create a virtual hard disk now" and click "Create". This will be the virtual equivalent of a hard drive for your VM.

5. Choose "VDI (VirtualBox Disk Image)" and click "Next".

6. Choose "Dynamically allocated" and click "Next". This means the virtual hard disk file will only grow as needed, up to the maximum size you specify.

7. Choose a location and size for your virtual hard disk. 20 GB is a good starting point for a Linux VM. Click "Create".

8. Your new VM should now appear in the VirtualBox Manager. Select it and click "Start".

9. VirtualBox will ask you for a start-up disk. This is the ISO file that contains the operating system you want to install. Download an Ubuntu ISO from the official [Ubuntu website](https://ubuntu.com/download/desktop) and select it here. The most recent version is recommended.

10. The Ubuntu installer should now start in your VM window. Follow the prompts to install Ubuntu.

## Reflection

- What challenges did you face while creating your VM? How did you overcome them?
- How much RAM and hard disk space did you allocate to your VM? Why did you choose these amounts?
- What do you think would happen if you allocated too much RAM to your VM?

# Configuring Your Virtual Machine

1. In the VirtualBox Manager, select your VM and click on "Settings".

2. In the "System" section, you can change the amount of memory and processors allocated to your VM. For now, leave these at their default values.

3. In the "Display" section, you can increase the amount of video memory to improve graphics performance. Bump this up to 128 MB.

4. In the "Storage" section, you can see your virtual hard disk and the ISO file mounted as a virtual CD/DVD drive. Once you've installed Ubuntu, you can remove the ISO by selecting it and clicking the remove disk icon.

5. Click "OK" to save your settings.

6. Start your VM and verify that it's running smoothly. Open some applications, browse the web, and perform some typical tasks.

## Reflection

- What settings did you change and why?
- How did your VM perform before and after changing the settings?
- What other settings do you think could be important for optimizing a VM's performance?
