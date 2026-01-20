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

## 1.4 Common Types of Networks

### 1.4.1 Networks of Many Sizes
Networks come in all sizes, ranging from simple networks consisting of two computers to networks connecting millions of devices.

* **Small Home Networks:** Connect a few computers to each other and to the internet.
* **Small Office and Home Office (SOHO) Networks:** Allow computers in a home office or a remote office to connect to a corporate network or access centralized, shared resources.
* **Medium to Large Networks:** Such as those used by corporations and schools, can have many locations with hundreds or thousands of interconnected hosts.
* **World Wide Networks:** The internet is a network of networks that connects hundreds of millions of computers world-wide.

---

## 1.4.2 LANs and WANs
Network infrastructures vary greatly in terms of:
* The size of the area covered.
* The number of users connected.
* The number and types of services available.

###  Local Area Network (LAN)
A LAN is a network infrastructure that provides access to users and end devices in a small geographical area.
* Interconnects end devices in a limited area such as a home, school, office building, or campus.
* Usually administered by a single organization or individual.
* Provides high-speed bandwidth to internal end devices.

###  Wide Area Network (WAN)
A WAN is a network infrastructure that provides access to other networks over a wide geographical area.
* Interconnects LANs over wide geographical areas such as between cities, states, provinces, nations, or continents.
* Typically managed by multiple service providers.
* Typically provides slower speed links between WANs.


## 1.4.3 Intranets and Extranets
* **Intranet:** A private connection of LANs and WANs that belongs to an organization. It is designed to be accessible only by the organization's members, employees, or others with authorization.
* **Extranet:** Provides secure and safe access to individuals who work for a different organization but require access to the organization's data (e.g., vendors, customers, or partners).




---
[⬅️ Back to Module Index](./README.md)
