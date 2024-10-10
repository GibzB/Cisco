# Network Exploration and Configuration

## Overview

This exercise provided hands-on experience using Cisco Packet Tracer to explore, configure, and manage network devices in both physical and logical modes. It helped me learn how to investigate a network setup, connect devices, and configure basic settings like hostnames. These tasks are relevant for real-world scenarios where network administrators need to understand their environment, connect devices properly, and ensure efficient network operations.

Below is a step-by-step breakdown of each part of the exercise, highlighting the key lessons and skills gained.

## Objectives

* Investigate the Bottom Toolbar
* Explore Devices in a Wiring Closet
* Connect End Devices to Networking Devices
* Install a Backup Router
* Configure a Hostname
* Explore the Rest of the Network

## Part 1: Investigate the Bottom Toolbar

The first part involved familiarizing myself with the bottom toolbar in Cisco Packet Tracer, particularly focusing on networking components such as Network Devices, End Devices, and Connections. This section taught me how to navigate the Packet Tracer interface and access various networking media like copper and fiber cables.

 **Lesson Learned** : Understanding the toolbar helped me quickly access essential tools, making it easier to build and manage a network in real-world tasks.

 **Screenshot Placement** : I will include a screenshot of the bottom toolbar here to provide a visual reference for identifying key categories.

![5](<Screenshot 2024-10-10 at 19.20.07.png>)

## Part 2: Investigate Devices in a Wiring Closet

This part involved exploring a branch office wiring closet in physical mode. I examined a rack containing routers, switches, and a wireless access point. I learned how to navigate the physical layout of network equipment and differentiate between devices that use wired or wireless connections.

 **Lesson Learned** : This section showed me how devices are physically organized in a rack, similar to real-world network installations. I also learned how to switch between physical and logical views for a more complete understanding of the network.

 **Screenshot Placement** : I will place a screenshot of the Branch Office Wiring Closet here, zooming in on the rack for clarity.

 ![4](<Screenshot 2024-10-10 at 19.21.03.png>)

## Part 3: Connect End Devices to Networking Devices

In this task, I connected end devices (like PCs and laptops) to network devices using copper straight-through and console cables. I learned how to properly connect devices using different types of cables for network and management connectivity.

 **Lesson Learned** : I gained practical skills in understanding how to physically connect devices, which is crucial when setting up network infrastructure in a business environment.

 **Screenshot Placement** : A screenshot of PC_1 connected to switch ALS2 with a copper straight-through cable will be placed here to illustrate the setup.

 ![6](<../Screenshot 2024-10-10 at 19.24.38.png>)

## Part 4: Install a Backup Router

I installed and powered on a backup router in the branch office, connecting it to a laptop using a USB cable. This task introduced me to modern networking practices, where USB is often used for configuration instead of the older RS232 port.

 **Lesson Learned** : This section helped me learn about modern network devices and how they are managed, which is highly applicable to the ever-evolving world of network infrastructure.

 **Screenshot Placement** : A screenshot of the Backup Router installation in the rack and its USB connection to Laptop_1 will go here for clarity.

![9](<../Screenshot 2024-10-10 at 19.26.04.png>)

## Part 5: Configure a Hostname

Using the terminal on Laptop_1, I configured the hostname of the Backup Router to "Edge_Router_Backup." This task reinforced my understanding of basic router configuration using CLI (Command-Line Interface).

```
Router> enable
Router# configure terminal
Enter configuration commands, one per line. End with CNTL/Z.
Router(config)# hostname Edge_Router_Backup
Edge_Router_Backup(config)# end
Edge_Router_Backup#
```

 **Lesson Learned** : Hostname configuration is essential for network administrators, as it provides a unique identifier for devices in a network. The hands-on experience with CLI commands is directly applicable to real-world network administration.

 **Screenshot Placement** : A screenshot of the terminal showing the hostname configuration process will be placed here.

## Part 6: Explore the Rest of the Network

The final part of the exercise allowed me to explore the network further, including areas like the Wellington Data Center and Teleworker Home. I explored different devices and configurations across various network setups.

 **Lesson Learned** : This part of the exercise highlighted how different parts of a network are interconnected and how technologies differ depending on the location. The hands-on exploration built my confidence in navigating complex networks.

## Conclusion

This Cisco Packet Tracer exercise provided invaluable hands-on experience that mirrors real-world network setup and administration. I learned how to navigate the Packet Tracer interface, connect devices, install backup routers, and configure settings like hostnames. The skills gained are essential for understanding how small to medium-sized business networks operate and how to troubleshoot and manage network devices effectively.

By exploring both the physical and logical modes, I now have a deeper understanding of network configurations and how they are applied in real-world scenarios.
![11](<Screenshot 2024-10-10 at 18.54.49.png>)