# Tool Familiarization

### 

### 1\) Wireshark — Packet Capture \& Analysis



##### &nbsp;          Wireshark is a software tool used to monitor the network traffic through a network interface.A network protocol analyzer that captures packets from live network traffic or from saved .pcap files.GUI-based, with powerful filtering and decoding of hundreds of protocols.It offers network monitoring on almost all types of network standards (ethernet, wlan, Bluetooth etc).It is open-source with a large community of backers and developers.All the necessary components for monitoring, analyzing and documenting the network traffic are present. It is free to use.





### 2\) Nmap — Network Scanning



##### &nbsp;           Nmap (Network Mapper) is a powerful tool that helps you discover and gather information about devices and services running on a network. In simple terms, Nmap is like a special tool that lets you see which computers or devices are connected to a network and what programs or applications are running on them.It is a a command-line tool for scanning hosts and networks.Reveals live hosts, open ports, services, versions, and OS detection.

##### 

##### Nmap allows you to:

##### 1\. Find live devices on a network.

##### 2\. Check which ports or doors are open on those devices.

##### 3\. Identify the services or applications running on those open ports.





### 3\) Burp Suite — Web Proxy for Testing



##### &nbsp;              An intercepting proxy for analyzing \& manipulating web traffic between browser and server.GUI tool, very popular among web penetration testers.Lets you see, intercept, modify, and replay HTTP/HTTPS requests.Useful for finding vulnerabilities like SQL injection, XSS, authentication flaws. vulnerabilities like SQL injection, XSS, authentication flaws.

##### 

##### Key features:

##### 

1. ##### Proxy: intercept browser traffic.
2. ##### Repeater: manually replay \& edit requests.
3. ##### Intruder: automate payload injection (e.g., fuzzing).
4. ##### Scanner (Pro version): automatically finds vulns.
5. ##### Decoder: encode/decode data (base64, URL-encoding).
6. ##### Comparer: compare two requests/responses.





### 4\) Netcat (nc) — Network Swiss Army Knife



##### &nbsp;                  Netcat is a versatile Unix utility that facilitates reading and writing data across network connections using either TCP or UDP protocols.Great for quick debugging, port testing, banner grabbing.Often used for reverse shells in penetration testing.

##### 

##### The following tasks can be done easily with Netcat:

##### 

* ##### Connect to a port of a target host.
* ##### Listen to a certain port for any inbound connections.
* ##### Send data across client and server once the connection is established.
* ##### Transfer files across the network once the connection is established.
* ##### Can execute programs and scripts of the client on the server and vice versa.
* ##### Can Provide remote shell access of server to a client where shell commands can be executed.



##### Key features:

##### 

* ##### Client mode: connect to a port.
* ##### Server mode: listen for incoming connections.
* ##### File transfer: send/receive raw files.
* ##### Port scanning (basic).
* ##### Chat / test connections.

##### 

##### Syntax:

##### nc \[options] \[hostname] \[port]

##### 

