![image](https://github.com/RIDWANE-EL-FILALI/NetPractice/blob/master/images/Net.png)
# General Knowledge
  ## What is a host :
  refers to any device or computer that is connected to a network and has a unique identity within that network. These devices can include computers, servers, laptops, smartphones, tablets, or any other device that can connect to a network, cloud resources are also considered a host, The same goes for internet of Things devices.
  hosts are divided into two parts **Clients** and **Servers** and the clients are the ones responsible for initiating data while the servers respond that just for a duration of time because a lot of devices can play both sides based on the situation
![client-server](https://github.com/RIDWANE-EL-FILALI/NetPractice/blob/master/images/Client.png)
  ## Ip address
  An IP (Internet Protocol) address is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. IP addresses serve two primary functions in networking:

* Device Identification: IP addresses are like digital addresses for devices on a network. Just as your home has a unique postal address to receive mail, each device on a network is assigned a unique IP address to send and receive data. This address helps identify the device and distinguish it from others on the same network. It typically looks like a sequence of numbers and periods, such as "192.168.1.1."

* Routing Data: IP addresses play a crucial role in routing data across networks. When you send data from your device to another device on the Internet, routers use the destination IP address to determine the path the data should take to reach its destination. Think of IP addresses as postal codes that guide data packets through the network to the correct recipient.

The ip addresses come in two main versions IPv4 and IPv6 which were introduced Due to the rapid growth of the Internet,
![image](https://github.com/RIDWANE-EL-FILALI/NetPractice/blob/master/images/Client%20(1).png)
So for the data passing the internet, there is a set of info latched into it containing the IP address of the sender and the receiver, the IP address helps us route the way for a packet.
You'll understand the hierarchically assigned in the chart below
![image](https://github.com/RIDWANE-EL-FILALI/NetPractice/blob/master/images/COR%2010.X.X.X.png)
so every department has its own network.

  ## Network :
  so to achieve the minimum requirement for a network is to connect at least two hosts together,
  After connecting the two hosts they're finally ready to talk to each other, now A network in a nutshell is a logical grouping of hosts that require similar connectivity where networks can contain other networks(Sub-Networks) and networks connect to other networks using the internet,
  ## Repeater :
  So the repeater only got introduced because of the decay of signals between hosts so the repeater does what its name signifies it repeats signals (regenerates signals) until it reaches the destination
  ![image](https://github.com/RIDWANE-EL-FILALI/NetPractice/blob/master/images/Net%20(1).png)
  ## Hub :
  A hub is a basic networking device that operates at the physical layer (Layer 1) of the OSI (Open Systems Interconnection) model. Its primary function is to connect multiple network devices together within the same local area network (LAN) and facilitate the transmission of data packets between them. However, it's important to note that hubs are not intelligent devices and lack the sophistication of more advanced networking equipment like switches and routers.
  ## Bridge :
  Now, let's delve into bridges. Bridges are more intelligent networking devices that operate at the data link layer (Layer 2) of the OSI model. Unlike hubs, bridges make decisions based on MAC (Media Access Control) addresses and can filter and forward data selectively. They play a crucial role in segmenting and optimizing network traffic within LANs. Understanding bridges is essential for building efficient and well-organized local networks.

By transitioning from hubs to bridges, you'll gain insights into how networking devices can be smarter and more selective in handling data, paving the way for further discussions on switches, routers, and more advanced networking concepts in subsequent chapters.
  ## Switch :
  A switch is a critical networking device that operates at the data link layer (Layer 2) of the OSI (Open Systems Interconnection) model. Its primary function is to intelligently forward data packets within a local area network (LAN) by using the Media Access Control (MAC) addresses of devices connected to it. Switches are a significant improvement over hubs because they are more efficient, provide faster data transmission, and allow for better network organization.

Here's a simple explanation of a switch:

A switch in networking is like a smart traffic cop at a busy intersection. When devices, such as computers or printers, on a network want to communicate with each other, they send data packets. The switch examines the MAC addresses on these packets and determines which device is the intended recipient. It then efficiently directs the data only to the specific device, ensuring that data traffic flows smoothly. Think of a switch as a device that optimizes communication in a network, reducing congestion and ensuring that data reaches its destination quickly and accurately.

Key points to remember about switches:

Efficient Data Forwarding: Switches make intelligent forwarding decisions based on MAC addresses, reducing unnecessary data broadcasts and collisions, which are common issues with hubs.

Segmentation: Switches can segment a network into smaller collision domains, meaning that data sent by one device doesn't collide with data sent by another, improving network performance.

Higher Speeds: Switches can operate at higher speeds, such as 1 Gbps or 10 Gbps, making them suitable for high-bandwidth applications.

Broadcast Control: Switches control and limit the scope of broadcast traffic, preventing unnecessary network congestion.

Port-Based: Each port on a switch connects to a single device, allowing for direct, point-to-point communication.

Common in LANs: Switches are commonly used in local area networks (LANs) to efficiently manage data traffic.

In summary, switches are like intelligent traffic managers for data in a network. They examine the MAC addresses of incoming data packets and make smart decisions about where to send the data, resulting in faster, more efficient, and less congested network communication. Switches are fundamental to modern networking and are a key component in most LANs and data centers.
![image](https://github.com/RIDWANE-EL-FILALI/NetPractice/blob/master/images/network_switch-2538506274)

## Routers :
A router is a crucial networking device that operates at the network layer (Layer 3) of the OSI (Open Systems Interconnection) model. Its primary function is to connect different networks together, determine the best path for data to travel between them, and forward data packets accordingly. Routers are responsible for directing data traffic across the vast global network known as the Internet and are integral to the functioning of modern networking.

Here's a straightforward explanation of a router:

A router in networking is like a post office for the internet. Just as the post office receives letters and parcels and determines the best routes for them to reach their destinations, a router receives data packets from your device and decides how to send them across the internet to reach their intended destinations. It does this by examining IP (Internet Protocol) addresses on the packets and using a combination of routing tables and algorithms to determine the most efficient path. Routers connect different networks together and ensure that data reaches its destination accurately and efficiently, whether it's across the globe or across the room.

Key points to remember about routers:

Network Connection: Routers connect multiple networks together, such as your local network (LAN) to the Internet, allowing devices on your network to communicate with devices on other networks.

IP Address Routing: Routers use IP addresses to make routing decisions. They maintain routing tables that contain information about the best paths for data to travel to reach specific IP addresses.

Firewall and Security: Many routers include firewall capabilities to protect your network from unauthorized access and provide security features like Network Address Translation (NAT).

DHCP: Routers often include a DHCP (Dynamic Host Configuration Protocol) server to assign IP addresses to devices on the local network automatically.

Quality of Service (QoS): Some routers support QoS settings, allowing you to prioritize certain types of traffic, such as video calls or online gaming, for a better user experience.

Gateway to the Internet: For home and small business networks, the router often serves as the gateway to the Internet, managing incoming and outgoing data traffic.

In summary, routers are like intelligent traffic directors for data on the internet and local networks. They make decisions about the best routes for data to follow, ensuring that it reaches its destination efficiently and securely. Routers are a fundamental component of internet connectivity, allowing us to access websites, send emails, stream videos, and perform countless other online activities.
![image](https://github.com/RIDWANE-EL-FILALI/NetPractice/blob/master/images/2011-11-29_132204.avif)

# OSI Model :

The OSI (Open Systems Interconnection) model is a conceptual framework that standardizes the functions of a telecommunication or networking system into seven distinct layers. These layers are designed to help ensure that different network devices and protocols can work together seamlessly. The OSI model does not represent an actual implementation but serves as a reference model for understanding how different network protocols and technologies interact.

Here are the seven layers of the OSI model, from the bottom (Layer 1) to the top (Layer 7), along with a brief description of each layer:

* Physical Layer:

This is the lowest layer of the OSI model.
It deals with the physical medium over which data is transmitted, such as cables, connectors, and network interface cards (NICs).
It defines the electrical, mechanical, and functional characteristics of the physical medium.
* Data Link Layer:

The Data Link Layer is responsible for creating a reliable link between two directly connected nodes, such as two computers on the same network segment.
It is divided into two sublayers: Logical Link Control (LLC) and Media Access Control (MAC).
LLC manages flow control and error checking, while MAC handles access to the physical medium (e.g., Ethernet or Wi-Fi).
* Network Layer:

The Network Layer is responsible for routing packets of data between different networks and subnets.
It uses logical addressing, such as IP (Internet Protocol), to determine the best path for data to travel from the source to the destination.
Routers operate at this layer.
* Transport Layer:

The Transport Layer ensures end-to-end communication, reliability, and data integrity between two devices across a network.
It manages data segmentation, flow control, error correction, and retransmission if necessary.
Protocols like TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) operate at this layer.

* Session Layer:

The Session Layer establishes, maintains, and terminates communication sessions between two devices.
It also manages synchronization, checkpointing, and recovery mechanisms during data exchange.
This layer ensures that data is exchanged properly, and if the connection is lost, it can be re-established.
* Presentation Layer:

The Presentation Layer is responsible for data translation, encryption, and compression.
It ensures that data is in a format that the application layer can understand, regardless of differences in data representation between systems.
* Application Layer:

The Application Layer is the topmost layer of the OSI model.
It provides a platform for application software to communicate over a network.
This layer contains various protocols and services for specific applications, such as HTTP for web browsing, FTP for file transfer, and SMTP for email.


It's important to note that the OSI model is a theoretical model, and not all networks and protocols neatly fit into its seven layers. The model primarily serves as a guide for understanding how network communication occurs and how different protocols and technologies interact in a layered fashion. Actual network protocols and implementations often combine functions from multiple OSI layers.

![image](https://github.com/RIDWANE-EL-FILALI/NetPractice/blob/master/images/osi-2947018831)

# TCP/IP :

The OSI (Open Systems Interconnection) model and the TCP/IP (Transmission Control Protocol/Internet Protocol) suite are both conceptual frameworks used to understand and standardize the functioning of computer networks. The relationship between the two can be explained as follows:

- Layer Mapping:

The OSI model consists of seven distinct layers, while the TCP/IP suite is organized into four layers. However, there's a mapping between these layers:
OSI Layer 7 (Application) roughly corresponds to the TCP/IP Application Layer.
OSI Layer 6 (Presentation) is often considered part of the TCP/IP Application Layer.
OSI Layer 5 (Session) is not explicitly represented in the TCP/IP model.
OSI Layer 4 (Transport) corresponds to the TCP/IP Transport Layer.
OSI Layer 3 (Network) corresponds to the TCP/IP Internet Layer.
OSI Layer 2 (Data Link) is not directly represented in the TCP/IP model; functions like addressing and framing are handled by various protocols at different layers in TCP/IP.
OSI Layer 1 (Physical) corresponds to the physical and link layers in TCP/IP (e.g., Ethernet, Wi-Fi).
Practical Implementation:

While the OSI model is more of a theoretical framework, the TCP/IP suite is a practical implementation used extensively in real-world networking, especially on the internet.
Most modern networks, including the internet, primarily use TCP/IP protocols for communication.
Now, let's explain the TCP/IP suite:

TCP/IP (Transmission Control Protocol/Internet Protocol):
TCP/IP is a comprehensive set of networking protocols and standards that form the foundation of the internet and many other networks. It includes the following key components:

- Network Layer (Internet Layer in TCP/IP):

Equivalent to OSI Layer 3.
Responsible for addressing and routing packets of data so they can be transmitted across networks.
The Internet Protocol (IP) is the core protocol at this layer, which provides logical addressing (IPv4 or IPv6) and routing.
- Transport Layer:

Equivalent to OSI Layer 4.
Provides end-to-end communication services, ensuring reliable data delivery, error detection, and error recovery.
TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are the two main protocols used in this layer.
- Application Layer:

Corresponds to OSI Layers 5, 6, and 7.
Contains various application-specific protocols and services that allow applications to communicate over the network.
Examples of protocols at this layer include HTTP (for web browsing), SMTP (for email), and FTP (for file transfer).
- Link Layer and Physical Layer:

These layers handle the actual transmission of data on the physical medium and are often not explicitly represented in the TCP/IP model. Instead, various protocols, such as Ethernet, Wi-Fi, and PPP, operate at these layers.
In summary, the TCP/IP suite is a practical networking model used for real-world communication, while the OSI model is a theoretical reference model. The TCP/IP suite has been crucial in the development and operation of the modern internet and many other networks, offering a simplified and efficient approach to network communication.

# Encapsulation and decapsulation :
Encapsulation and decapsulation are fundamental processes in networking and data communication. Encapsulation involves the packaging of data as it moves down the protocol stack, where each layer adds its own header information to the original data. This layered structure, represented by the OSI or TCP/IP model, allows for modularity and standardized communication. Decapsulation, on the other hand, occurs as data travels up the protocol stack. At each layer, the corresponding header is stripped off, and the relevant information is processed or forwarded to the next layer. This process ensures that data is correctly handled and delivered across the network, with each layer responsible for specific functions such as addressing, error checking, or routing. Encapsulation and decapsulation together enable seamless communication and interoperability in complex networking environments.

The images below will actually explain it more then words ever can :
![image](https://github.com/RIDWANE-EL-FILALI/NetPractice/blob/master/images/csg25-03-tcp-ip-encapsulation-3184591302)
![image](https://github.com/RIDWANE-EL-FILALI/NetPractice/blob/master/images/fig006-4230982733)


