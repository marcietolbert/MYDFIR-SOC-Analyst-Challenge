# Logical Diagram

## Introduction
In the MYDFIR SOC Analyst Challenge, day one required me to create a logical diagram for the project. I was eager to tackle this task as I understood the importance of being able to create logical diagrams. In the passages that follow, I will explain the technical aspects of creating both a static and animated diagram. First, however, let's delve into the theory of network diagrams.

## What is a Logical Diagram
So, just what is a logical diagram? First, I'll start by defining what a network diagram is. A network diagram is a visual representation of a computer or telecommunications network that uses icons and lines to depict the devices within an environment and how they are connected. Network diagrams can fall into two categories: physical and logical. A physical diagram illustrates the physical components and connections within a network. In a physical diagram, icons represent the different devices in the environment, while the lines show the cable connections between the devices. 

In contrast, a logical network diagram shows how devices communicate with each other. Similar to a physical diagram, a logical diagram depicts various devices within an environment. However, instead of the lines representing physical cabling, the lines represent data flow. Therefore, I need to create a network diagram that depicts both the devices within the environment and how data flows between them.

Here are some of the most common types of symbols that can be found in a logical diagram.

![image7-3](https://github.com/user-attachments/assets/08c5f8f3-1465-43b6-8e27-b4a576a825e7)
*Photo: via <a href="https://miro.com/blog/network-diagram/">Miro</a>*
<br>
<br>
![image1-10](https://github.com/user-attachments/assets/f4885289-be80-4347-a1c4-8406e79b23bd)
*Photo: via <a href="https://miro.com/blog/network-diagram/">Miro</a>*

## Logical Diagram Requirements
To begin constructing the logical diagram that will serve as the visual representation of the SOC environment I am building, I need to know what devices and environments I need to include in the diagram. The day-one video mentioned that my diagram should include the Internet, a Vultr cloud, a VPC (virtual private cloud), six servers, an Internet Gateway, and two computers. I'll be using Draw.io to create my logical diagram.

The devices to be depicted in the diagram are as follows:
- Elastic & Kibana Server
- Windows Server (RDP enabled)
- Ubuntu Server (SSH enabled)
- Fleet Server
- osTicket Server
- C2 Server (Mythic)
- Internet Gateway (Internet Service Provider)
- Computer (SOC Analyst laptop)
- Computer (Attacker laptop, Kali Linux OS)

The diagram should also include the following information about the VPC network:
- Private Network: 172.31.0.0/24
- IP Range: 172.31.0.1-254
- Subnet Mask: 255.255.255.0

## Device Connections and Data Flow
This section will cover where the devices for this project are placed in the enviroment and how show how data will flow between them. 
<br>
<br>

*Image 1: Static Logical Diagram*
<br>
<br>

*Image 2: Animated Logical Diagram*

The images above are the static and animated logical diagrams I created for this project. The breakdown of the devices and connections are as follows:


