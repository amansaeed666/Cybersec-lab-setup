# Cybersec-lab-setup
# Kali Linux Virtual Machine Lab Setup

## Introduction

The purpose of this lab was to create and configure a **Kali Linux Virtual Machine** using **Oracle VirtualBox**. Kali Linux is a Linux-based operating system commonly used for cybersecurity, networking, and security testing. VirtualBox provides a virtual environment where Kali Linux can run separately from the main operating system.

---

## Step 1: Download VirtualBox

The first step was to download **Oracle VirtualBox**. VirtualBox is virtualization software that allows users to create and run virtual machines on their computer.

It provides a virtual environment for installing and testing different operating systems without affecting the main operating system.

---

## Step 2: Install VirtualBox

After downloading VirtualBox, the installation process was completed by following the installation instructions.

Once the installation was finished, VirtualBox was opened to create and configure a new virtual machine for Kali Linux.

---

## Step 3: Download Kali Linux ISO Image

The **Kali Linux ISO image** was downloaded for installation.

An ISO image contains the installation files required to install an operating system. This ISO file was used as the installation source for the Kali Linux virtual machine.

---

## Step 4: Import the Kali Linux ISO Image and Install Kali Linux

A new virtual machine was created in VirtualBox, and the Kali Linux ISO image was attached to the virtual machine.

The virtual machine was then started, and the Kali Linux installation process was completed. After configuring the required installation settings, Kali Linux was successfully installed and became ready to use.

---

## Step 5: Create and Configure a NAT Network

A NAT Network was created in Oracle VirtualBox through the Network Manager to provide network connectivity for the virtual machine.

The NAT Network was configured with the following settings:

- **Network Name:** NatNetwork
- **IPv4 Prefix:** 10.0.0.0/24
- **DHCP:** Enabled

The NAT Network allows the Kali Linux virtual machine to communicate through the host computer's network connection. DHCP was enabled to automatically manage IP address assignment within the network.

**Screenshot: NAT Network Configuration**

> Add the NAT Network screenshot here showing the `10.0.0.0/24` IPv4 prefix.

---

## Step 6: Configure the Virtual Machine Network Adapter

The network settings of the Kali Linux virtual machine were configured in VirtualBox.

The network adapter was enabled and attached to the appropriate NAT network. This configuration allows the Kali Linux virtual machine to access the network through VirtualBox.

The virtual cable connection was also enabled to ensure proper communication between the virtual machine and the configured network.

---

## Step 7: Start the Kali Linux Virtual Machine

After completing the installation and network configuration, the Kali Linux virtual machine was started successfully.

The Kali Linux login screen appeared, confirming that the operating system was correctly installed and running inside VirtualBox.

The completed virtual machine environment is now ready for networking and cybersecurity practice.

---

## Lab Setup Summary

| Step | Task | Description |
|------|------|-------------|
| 1 | Download VirtualBox | Download the virtualization software. |
| 2 | Install VirtualBox | Install VirtualBox on the host computer. |
| 3 | Download Kali Linux ISO | Download the Kali Linux installation image. |
| 4 | Install Kali Linux | Attach the ISO image and install Kali Linux. |
| 5 | Create NAT Network | Configure a NAT Network with the `10.0.0.0/24` IPv4 prefix. |
| 6 | Configure Network Adapter | Enable and configure network connectivity for the virtual machine. |
| 7 | Start Kali Linux | Launch the Kali Linux virtual machine and verify the installation. |

## Conclusion

In this lab, a Kali Linux virtual machine was successfully created using Oracle VirtualBox. The Kali Linux operating system was installed using an ISO image, and a NAT Network with the IPv4 prefix **10.0.0.0/24** was configured to provide network connectivity. The completed lab environment can now be used for networking, cybersecurity, and security testing practice.
