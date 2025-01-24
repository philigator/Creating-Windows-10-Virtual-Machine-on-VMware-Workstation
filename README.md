# How to Create a Windows 10 Virtual Machine on VMware

## Installing Windows 10

**Note:** If any step does not include specific instructions for a particular setting, it is recommended to use the default option provided by VMware for that step.

### Step 1: Create a New Virtual Machine
- Open VMware Player.
- Select **Create a New Virtual Machine**.

![image](https://github.com/user-attachments/assets/8d992598-24fd-4520-92f8-069fb5f2c33a)

### Step 2: Choose Configuration Type
- Select **Custom (advanced)**.
- Click **Next** on the "Choose the Virtual Machine Hardware Compatibility" window.

![image](https://github.com/user-attachments/assets/97a11f9a-1f54-4cb5-a212-070ec0ab272c)

### Step 3: Specify Installation Media
- On the "Guest Operating System Installation" window, select **Installer disc image file (iso):**.
- Browse for the Windows 10 ISO file and click **Next**.

![image](https://github.com/user-attachments/assets/071a2faa-b730-4426-9292-7712ad54d21a)

### Step 4: Select Guest Operating System
- On the "Easy Install Information" window, under **Version of Windows to install**.
- Select the version of Windows 10 you are installing.
- Under "Personalize Windows: Enter Full Name:. Click **Next**.

![image](https://github.com/user-attachments/assets/ce609bdb-b5e2-41c8-a502-81407189c986)
![image](https://github.com/user-attachments/assets/8ed38aec-0569-4fc0-a349-7be7049dc95c)


### Step 5: Name the Virtual Machine
- Enter a recognizable name for your virtual machine (e.g., "Windows10_VM").
- Under "Location," click **Browse** and select a folder to store the virtual machine files. Click **Next**.

![image](https://github.com/user-attachments/assets/e4b6fc40-7521-49d0-b390-637b6dbf48a4)

### Step 6: Configure Processor Settings
- On the "Processor Configuration" window, allocate at least **2 processors** and **1 core per processor**. Click **Next**.

![image](https://github.com/user-attachments/assets/c6a344e9-14d0-4fe5-b8cf-105d463c2751)

### Step 7: Configure Memory
- If your system has **16GB or more of RAM**, allocate at least **4GB (4096MB)** of memory for the virtual machine.
- If your system has less than **16GB of RAM**, allocate **2GB (2048MB)** instead. Note that the virtual machine may perform slower with reduced memory.
- Click **Next**.

![image](https://github.com/user-attachments/assets/6aea9072-4dfc-4af9-9913-0251ccb48769)

### Step 8: Configure Network Settings
- Choose a network type:
   - Bridged: Use this if you want the virtual machine to have direct access to your network, appearing as a separate device. Ideal for testing or when a unique IP address is required.
   - NAT: Use this if you prefer the virtual machine to share the host's IP address, providing easier setup and added security behind the host's firewall.
- Click **Next**.

![image](https://github.com/user-attachments/assets/34babd6b-e48a-4b79-abdf-36864938d05d)

### Step 9: Set I/O Controller Type
- Leave the recommended settings and click **Next**.

![image](https://github.com/user-attachments/assets/1a827b5a-047e-4e98-bcf4-acbf160e2352)

### Step 10: Select Disk Type
- Leave the recommended settings and click **Next**.

![image](https://github.com/user-attachments/assets/61ab3bec-3274-4e49-82c6-88a34aedebd7)

### Step 11: Create a New Virtual Disk
- Choose **Create a new virtual disk** and click **Next**.

![image](https://github.com/user-attachments/assets/0092eb95-e2d7-415e-b4ad-32770b12c285)

### Step 12: Specify Disk Capacity
- Set the disk size to at least **60GB**.
- Select **Split virtual disk into multiple files**. Click **Next**.

![image](https://github.com/user-attachments/assets/f58bb632-ac29-4a5a-a627-22aa5e5073fe)

### Step 13: Specify Disk File
- Click **Next** on the "Specify Disk File" window.

![image](https://github.com/user-attachments/assets/94b8fc6f-bdb7-437e-8476-2b7edd0772a7)

### Step 14: Review and Finish
- Review the virtual machine settings.
- Click **Finish** to create the virtual machine.

![image](https://github.com/user-attachments/assets/de732d08-7dcf-42ba-a194-5974ac12e370)

### Step 15: Power On the Virtual Machine
- Select **Power on this virtual machine** to start the Windows 10 installation.

![image](https://github.com/user-attachments/assets/09f697b6-6612-4a63-80ba-5d069cf11e92)

---

## Installing VMware Tools (Optional)

Note: This step is optional if VMware Tools have not been installed. You can verify this by clicking on the **"VM"** tab at the top of VMware Player.

- If the bottom option says **"Install VMware Tools"**, follow these steps to install it.
- If it says **"Reinstall VMware Tools"** but is grayed out, VMware Tools are already installed, and you can skip this step.

### Step 1: Mount VMware Tools
- Right-click on the virtual machine tab and select **Install VMware Tools**.

### Step 2: Access VMware Tools
- In the virtual machine, open the **File Explorer**.
- Navigate to the VMware Tools drive and run the installer.

### Step 3: Follow the Installation Wizard
- Complete the installation process using the VMware Tools setup wizard.

### Step 4: Restart the Virtual Machine
- Reboot the virtual machine to apply VMware Tools.

---

This guide provides a step-by-step approach to creating and configuring a Windows 10 virtual machine on VMware. For further customization or troubleshooting, refer to the VMware documentation or community forums.

