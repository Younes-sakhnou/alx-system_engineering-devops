# OSI Model Readme

## What is the OSI Model?
The OSI (Open Systems Interconnection) model is a conceptual framework that standardizes how different network protocols and communication technologies interact and communicate with each other. It provides a structured approach for understanding and organizing networking functions.

## How many layers does it have?
The OSI model consists of seven layers, each serving a specific purpose in the communication process. The layers are organized in a hierarchical manner, with each layer depending on the services provided by the layer below it.

## How is it organized?
The OSI model is organized from the bottom layer to the top layer as follows:
1. Physical Layer
2. Data Link Layer
3. Network Layer
4. Transport Layer
5. Session Layer
6. Presentation Layer
7. Application Layer

## What is a LAN (Local Area Network)?
A LAN is a network of interconnected devices located within a small geographical area, such as a home, office, or campus. It enables devices like computers, printers, and smartphones to communicate and share resources with each other.

### Typical Usage:
LANs are commonly used in homes and businesses to facilitate file sharing, internet access, and local communication.

### Typical Geographical Size:
The size of a LAN typically covers a limited area, ranging from a few meters to a few kilometers.

## What is a WAN (Wide Area Network)?
A WAN is a network that spans over a large geographical area, connecting multiple LANs or devices over long distances. It relies on public or private telecommunication infrastructure.

### Typical Usage:
WANs are used to connect remote locations, offices, or even countries, enabling data transfer and communication between geographically distant devices.

### Typical Geographical Size:
The geographical size of a WAN can span vast distances, covering cities, countries, or even continents.

## What is the Internet?
The Internet is a massive global network of interconnected computers and devices. It connects millions of networks worldwide, enabling communication and data exchange between users and services across the globe.

## What is an IP address?
An IP (Internet Protocol) address is a unique numerical label assigned to each device connected to a network. It serves as an identifier, allowing devices to send and receive data to specific destinations.

## What are the 2 types of IP addresses?
There are two types of IP addresses: IPv4 and IPv6. IPv4 is the older version and uses a 32-bit address format, while IPv6 is the newer version and uses a 128-bit address format, allowing for a significantly larger number of unique addresses.

## What is localhost?
"Localhost" is a special hostname that refers to the current device or computer you are using. It is commonly used to access services or applications running on the same device.

## What is a subnet?
A subnet is a portion of a larger network that is created by dividing the IP address range of the main network. It helps in organizing and managing IP addresses efficiently.

## Why IPv6 was created?
IPv6 was created to address the depletion of available IPv4 addresses due to the rapid growth of the internet. With its larger address space, IPv6 provides enough unique addresses to accommodate the ever-expanding number of devices and users connected to the internet.

## TCP/UDP
TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are two transport layer protocols used for data transfer in IP networks.

## What are the 2 mainly used data transfer protocols for IP?
The two mainly used data transfer protocols for IP are TCP and UDP.

## What is the main difference between TCP and UDP?
The main difference between TCP and UDP is how they handle data transmission. TCP provides reliable, ordered, and error-checked data delivery, ensuring that all data is received correctly. UDP, on the other hand, is faster but provides no guarantees for data delivery, making it suitable for real-time applications and situations where occasional data loss is acceptable.

## What is a port?
A port is like a special door on a computer that allows it to send and receive specific types of information. Different ports are used for different services or applications, like web browsing (port 80 for HTTP) or secure web browsing (port 443 for HTTPS).

## Memorize SSH, HTTP, and HTTPS port numbers
- SSH (Secure Shell): Port number 22
- HTTP (Hypertext Transfer Protocol): Port number 80
- HTTPS (Hypertext Transfer Protocol Secure): Port number 443

## What tool/protocol is often used to check if a device is connected to a network?
The "ping" command, which uses ICMP (Internet Control Message Protocol), is often used to check if a device is connected to a network. It sends a small packet to the target device and waits for a response, confirming the device's connectivity.
