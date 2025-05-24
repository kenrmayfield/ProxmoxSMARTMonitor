Hello everyone! 👋 I'm a tech enthusiast who loves testing things at home and running a small homelab. I currently have two Proxmox hosts running various services. These aren’t "enterprise-grade servers" just "regular machines" and I don’t have RAID setups to have greater redundancy or remote management interfaces like iDRAC or iLO to easily check disk health.

While Proxmox includes a SMART tool, I found it limited and not very user-friendly. I tried several other tools, but most were either too complex to set up or didn’t really work for my needs.

So, with zero programming experience and a lot of help from artificial intelligence, I created ProxmoxSMARTMonitor, a simple, visual, and easy-to-use web tool to check the health of your disks on a Proxmox server.

🚀 Installation & Usage
Follow these steps to get ProxmoxSMARTMonitor up and running:

1.  Install Dependencies

    ```bash
    sudo apt update
    sudo apt install python3 python3-pip
    pip3 install flask paramiko
    ```
2.  Download the Project

    ```bash
    git clone [https://github.com/mesteve123/ProxmoxSMARTMonitor](https://github.com/mesteve123/ProxmoxSMARTMonitor)
    ```
3.  Run the Application

    ```bash
    cd ProxmoxSMARTMonitor
    python3 app.py
    ```

🎥 Installation Demo

The [video](https://youtu.be/daRtsYX6keY) demonstrates the installation of ProxmoxSMARTMonitor, including:

* Cloning the GitHub repository [00:04]
* Navigating into the directory [00:11]
* Making the install script executable [00:14]
* Running the install script [00:17]

The presenter confirms the successful installation by showing the Proxmox SMART Monitor service running [02:54].

⚠️ Please note:
This application has only been tested on Ubuntu Server 22.04, so we recommend using it in that environment for now. I'm currently working on improving compatibility and developing a Docker version.

This tool was created primarily with the help of AI. Its correct functioning is not guaranteed, and it is not recommended for use in professional environments.

If you’d like to support more projects like this, donations are appreciated. You can do so from the link at the bottom of the application.

Thanks for stopping by! I'm open to feedback, suggestions, and contributions. Every bit of help is welcome 🙌
