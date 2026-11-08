# Cybersec-lab-setup
# Week 1: Cybersecurity Lab Setup for Networkwalks

## About

This repository documents the **Week 1 Cybersecurity Lab Setup for the Networkwalks project**. The main focus of this week was to prepare a virtual cybersecurity lab environment that can be used for networking and security-related practical tasks.

The lab environment was created using **Oracle VirtualBox** and **Kali Linux**. Kali Linux provides a suitable platform for learning cybersecurity concepts, network analysis, and security testing in a controlled virtual environment.

This setup will serve as the foundation for the upcoming practical activities and tasks in the Networkwalks project.

---

## Project Goal

The goal of the **Networkwalks project** is to develop practical knowledge and skills in networking and cybersecurity through hands-on laboratory activities.

The main objectives of this lab setup are to:

- Create a safe and isolated environment for cybersecurity practice.
- Install and configure Kali Linux as a virtual machine.
- Configure network connectivity using a NAT Network.
- Prepare a foundation for future networking and cybersecurity experiments.
- Develop practical skills through hands-on learning and testing.

---

# Kali Linux Virtual Machine Lab Setup

## Introduction

As part of **Week 1 of the Networkwalks Cybersecurity Lab**, the first task was to prepare the basic virtual lab environment. A Kali Linux virtual machine was created using Oracle VirtualBox.

The purpose of this setup is to provide a controlled environment where networking and cybersecurity concepts can be practiced without affecting the main operating system. The virtual lab will be used in future project activities for network configuration, security testing, and other cybersecurity experiments.

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

The completed virtual machine environment is now ready for future networking and cybersecurity practice.

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

During **Week 1 of the Networkwalks project**, a basic cybersecurity lab environment was successfully prepared. Oracle VirtualBox was installed, Kali Linux was configured as a virtual machine, and a NAT Network was created to provide network connectivity.

This lab setup provides a strong foundation for the upcoming networking and cybersecurity tasks and will support practical learning throughout the Networkwalks project.
