# 1.2 Network Components

## 1.2.1 Host Roles
Every computer on a network is called a **host** or **end device**. 
* **IP Addresses:** Hosts are identified by a unique number called an Internet Protocol (IP) address.
* **Servers:** Computers with software that allow them to provide information (like email or web pages) to other devices.
* **Clients:** Computers with software for requesting and displaying information obtained from a server.

### Common Server Types
| Type | Description |
| :--- | :--- |
| **Email** | Runs email server software; clients use mail client software (like Outlook) to access mail. |
| **Web** | Runs web server software; clients use browser software to access web pages. |
| **File** | Stores corporate and user files in a central location for client access. |

---

## 1.2.2 Peer-to-Peer (P2P)
In small businesses or homes, many computers function as both servers and clients at the same time.

**Advantages:**
* Easy to set up and less complex.
* Lower cost (no dedicated servers required).
* Good for simple tasks like file/printer sharing.

**Disadvantages:**
* No centralized administration.
* Not as secure or scalable.
* Performance can be slow as devices perform multiple roles.

---

## 1.2.3 End Devices
An end device is either the **source** or the **destination** of a message transmitted over the network. To distinguish them, each end device has a unique address.


---

## 1.2.4 Intermediary Devices
Intermediary devices connect individual end devices to the network or connect multiple networks together to form an internetwork. They use the destination address to determine the path that messages should take.

**Examples include:**
* Wireless Routers
* LAN Switches
* Routers
* Firewalls


---

## 1.2.5 Network Media
The medium provides the channel over which the message travels from source to destination. Modern networks primarily use three types:

1. **Metal wires within cables (Copper):** Data is encoded into electrical impulses.
2. **Glass or plastic fibers (Fiber-optic):** Data is encoded into pulses of light.
3. **Wireless transmission:** Data is encoded via modulation of specific frequencies of electromagnetic waves.

   # 1.3 Network Representations and Topologies

## 1.3.1 Network Representations
Network architects and administrators use symbols to represent the various devices and connections that make up a network. These diagrams allow them to see where components are located and how they are interconnected.

### Key Connection Terminology
* **Network Interface Card (NIC):** A NIC physically connects the end device to the network.
* **Physical Port:** A connector or outlet on a networking device where the media connects to an end device or another networking device.
* **Interface:** Specialized ports on a networking device that connect to individual networks. Because routers connect networks, the ports on a router are referred to as network interfaces.
* *Note: The terms "port" and "interface" are often used interchangeably.*

---

## 1.3.2 Topology Diagrams
Topology diagrams are mandatory documentation for anyone working with a network. They provide a visual map of how the network is connected. There are two primary types:

### Physical Topology Diagrams
These diagrams illustrate the **physical location** of intermediary devices and cable installation. They typically label specific rooms or locations where equipment is installed.


### Logical Topology Diagrams
These diagrams illustrate **devices, ports, and the addressing scheme** of the network. They show which end devices are connected to which intermediary devices and the type of media being used, regardless of their physical location.


| Feature | Physical Topology | Logical Topology |
| :--- | :--- | :--- |
| **Focus** | Physical location and cabling | Data flow, ports, and IP addressing |
| **Labels** | Room numbers, rack locations | Interface names (e.g., G0/1) and IP networks |
| **Purpose** | Installation and maintenance | Configuration and troubleshooting |


---
[⬅️ Back to Module Index](./README.md)
