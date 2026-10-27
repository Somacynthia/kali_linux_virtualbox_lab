# Week 1: Cybersecurity Lab Setup

## Project Overview
This project documents my Week 1 cybersecurity internship task: setting up a Kali Linux testing environment using Oracle VirtualBox.

## Objectives
- Set up Kali Linux as a virtual machine.
- Configure the required virtual network.
- Verify internet connectivity.
- Configure shared-folder access.
- Enable clipboard and drag-and-drop integration.
- Create a VirtualBox snapshot.

## Lab Configuration

| Component | Configuration |
|---|---|
| Virtualization platform | Oracle VirtualBox |
| Operating system | Kali Linux |
| Network type | NAT Network |
| Network subnet | `10.0.0.0/24` |
| Kali Linux IP address | `10.0.0.2/24` |
| Internet connectivity | Verified |
| Shared folder | Downloads |
| Snapshot | Week 1 - Kali Lab Setup |

## Verification Commands

Check IP configuration:

```bash
ip -4 addr
```

Test internet connectivity:

```bash
ping -c 4 google.com
```

Check shared-folder access:

```bash
ls -la /media/sf_Downloads
```

## Evidence

Screenshots of the lab setup, network configuration, connectivity tests, shared-folder access, and VirtualBox snapshot are included in this repository.

## Key Learnings
- Virtual machine configuration
- IP addressing and virtual networking
- Linux terminal commands
- Network connectivity testing
- Shared-folder permissions
- Virtual machine snapshots

## Purpose
This project is part of my ongoing cybersecurity learning journey and provides a foundation for future ethical hacking and penetration-testing exercises.
