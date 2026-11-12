# Linux OS Deployment & Administration (Zorin OS)

## 📌 Project Overview
This project involved deploying a Linux-based operating system (Zorin OS 18.1 Core) on a Virtual Machine using VMware Workstation Pro. The objective was to gain hands-on experience with virtualization, OS installation, system performance management, and security configurations.

## Technical Implementation

**1. OS Installation & Virtualization:**
*   Downloaded the Zorin OS ISO and configured a new VM in VMware Workstation Pro.
*   Allocated system resources (120GB virtual disk, 2 CPU cores, 4GB RAM) and configured the boot sequence.
*   *Troubleshooting:* Resolved a boot prompt issue post-installation by reconfiguring the VM's CD/DVD drive settings to point back to the ISO image.

**2. Software & Package Management:**
*   Installed applications using the Zorin OS Software Store (VLC, GIMP) and resolved external package dependencies by installing a `.deb` package for Google Chrome.

**3. System Performance Management:**
*   Utilized the Linux **System Monitor** to analyze real-time resource allocation.
*   Monitored CPU and RAM usage spikes while running resource-intensive applications (Chrome, VLC, GIMP) simultaneously to evaluate the OS's multitasking capabilities and process prioritization.

**4. Security Management (Linux Terminal):**
*   **User Access:** Configured secure user accounts and administrative privileges.
*   **Software Updates:** Ran the Software Updater to patch system vulnerabilities and configure AppArmor.
*   **Firewall Configuration:** Utilized the Linux terminal to check and enable the Uncomplicated Firewall (UFW) using `sudo ufw enable`, ensuring the system was protected against unauthorized network traffic.

## Key Takeaways
Deploying Zorin OS provided a deep understanding of how Linux environments handle virtualization, package management, and security. Navigating the system as Windows users required adaptability, but troubleshooting the VM boot process and configuring the UFW firewall provided valuable real-world IT administration experience.

---
*Course: DCS1106 – Operating System | INTI International College Subang*
