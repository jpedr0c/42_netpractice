<p align="center">
<a href="https://github.com/jpedr0c/42_netpractice">
<img src="images/netpractice.png" height="120" width="120">
</a>
</p>
<h1 align=center>
  <strong> NETPRACTICE </strong>
</h1>

<p align="center">
  <sub> Netpractice is the configuration of a small scale network using TCP/IP addressing.
  <sub>
</p>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)](#table-of-contents)

<p align="center">
  <a href="#About"> 💡 About the project </a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Explanation"> 📝 Explanation </a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Levels"> 📷 Levels</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#Credits"> 🏆 Credits</a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

<br/>

<a id="About"></a>
## 💡 About the project
> In this project the goal is to configure small scale networks using TCP/IP addressing. Networks are not real. Will be available through a browser-based training interface

<br/>

<a id="Explanation"></a>
## 📝 Explanation

### TCP - Transmission Control Protocol
- TCP is a communication standard that allowns programs, applications and devices to exchange messages over a network.
- It's used to send packets over the internet.
- It ensures the integrity of the data being transmitted over a network.
- It divides large amounts of data into smaller packets, ensuring end-to-end delivery without data loss.

#

### IP Address
- It's part of an Internet protocol suite, which also includes TCP.
- The Internet Protocol suite governs the rules for packaging, addressing, transmitting, routing and receiving data across networks.
- IP addressing is a logical means of assigning addresses to devices on a network.
- Each device connected to the Internet requires a unique IP address.
- An IP address has two parts: it identifies the host and it identifies the network.
- TCP/IP uses a subnet mask to separete them.
  #### IPv4
  - Defines an IP address as a 32-bit number.
  - It has more than 4.3 billion addresses.
  - IP addresses must be reused and mask and uses Numeric Dot-Decimal Notation.
  - E.g.: 192.168.42.23
  - Must be configures manually.
  #### IPv6
  - Defines an IP address as a 128-bit number.
  - It has more than 340 undecillion addresses.
  - Each device can have its own unique IP address and uses alphanumeric hexadecimal notation.
  - E.g.: 163f:6dee:0231:0042:0100:8c2e:0370:7286
  - Support automatic configuration.

#

### Subnet Mask
- It's a 32-bit address used to distinguish between a network address and a host address in the IP address.
- It's a network within a network. Subnets make networks more efficient.
- Subnetting is the process of stealing bits from the HOST part of the IP address to divide the large network into smaller ones called subnets.
- That's, define the range of IP addresses that can be used in a network or subnet.
- By may of the subnet, network traffic can travel a shorter distance without going through unnecessary routes to reach its destination.

#

### Switch
- Connects multiple devices on a single network, usually on a LAN (local area network).
- Unlike a router, a switch simply sends data to the devices it's intended for, which can be anothes switch, router or computer.
- It has no interfaces, as it only distributes packets to its local network and can't communicate directly with a network outside its own.

#

### Router
- The router connects several network together or packet-switched subnets.
- It manages traffic between these networks by forwarding data packets to their intended IP addresses and allowing multiple devices to use the same Internet connection.
- The router has one interface for each network it connects to.
- Because the router separates different networks, the range of possible IP addresses on one of its interface must not overlap with the range on its other interfaces.
- An overlap in the IP address range would imply that the interfaces are on the same network.
- To send packets efficiently, it uses an internal routing table (Routing Table), which is a list of paths to varios network destinations.
- A router reads a packet header to determine where it's going and then consults the routing table to decide which path is the most efficient for the packet to reack its destination.

#

### Routing Table
- This is a table of data stored on a router or network host that lists the routes to certain network destinations.

  #### Destination:
  - Specifies a network address at which a host is the final destination of packets.
  - The default route or 0.0.0.0/0 is the route that takes effect when no other route is available to a destination IP address.
  - The default route will use the address of the next hop to send packets on its way without providing a specific destination.
  - The default route will match any network.
  
  #### Next hop:
  - Refers to the next closest router that a packet can pass through.
  - This is the IP address of the next router in the packet's path.

<br/>

<a id="Levels"></a>
## 📷 Levels

<details>
<summary>Level 1</summary>
<br/>
<img src="images/level1.jpeg?raw=true" alt="level1">
<br/>
</details>

---

<details>
<summary>Level 2</summary>
<br/>
<img src="images/level2.jpeg?raw=true" alt="level2">
<br/>
</details>

---

<details>
<summary>Level 3</summary>
<br/>
<img src="images/level3.jpeg?raw=true" alt="level3">
<br/>
</details>

---

<details>
<summary>Level 4</summary>
<br/>
<img src="images/level4.jpeg?raw=true" alt="level4">
<br/>
</details>

---

<details>
<summary>Level 5</summary>
<br/>
<img src="images/level5.jpeg?raw=true" alt="level5">
<br/>
</details>

---

<details>
<summary>Level 6</summary>
<br/>
<img src="images/level6.jpeg?raw=true" alt="level6">
<br/>
</details>

---

<details>
<summary>Level 7</summary>
<br/>
<img src="images/level7.jpeg?raw=true" alt="level7">
<br/>
</details>

---

<details>
<summary>Level 8</summary>
<br/>
<img src="images/level8.jpeg?raw=true" alt="level8">
<br/>
</details>

---

<details>
<summary>Level 9</summary>
<br/>
<img src="images/level9.jpeg?raw=true" alt="level9">
<br/>
</details>

---

<details>
<summary>Level 10</summary>
<br/>
<img src="images/level10.jpeg?raw=true" alt="level10">
<br/>
</details>

<br/>

<a id="Credits"></a>
## 🏆 Credits
<div>
  
| [<img src="https://avatars.githubusercontent.com/u/78514252?v=4" width="300" style="border-radius:50%"><br><sub> João Pedro </sub>](https://www.linkedin.com/in/jpedroc) | <p align="justify">***Thank you for taking the time to review my project. If you have any questions or would like to connect with me, please feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/jpedroc)***</p> | 
|---|---|
  
</div>
