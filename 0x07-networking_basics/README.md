# Networking basics #0
Basics of networking: OSI Model , LAN, WLAN, Internet, IP addresses (IPv4, IPv6), TCP/UDP (Transmission Control Protocol, User Diagram Protocol), Ports (SSH: 22, HTTP: 80, HTTPS: 443), ping (protocol used to check if device is connected to network, netstat (display network connections, listening port

## Tasks :page_with_curl:

* **0. OSI model**
  * [0-OSI_model](./0-OSI_model): Text file answering the following questions:
  * What is the OSI model?
    1. Set of specifications that network hardware manufacturers must respect
    2. The OSI model is a conceptual model that characterizes the communication
    functions of a telecommunication system without regard to their underlying
    internal structure and technology.
    3. The OSI model is a model that characterizes the communication functions
    of a telecommunication system with a strong regard for their underlying
    internal structure and technology.
  * How is the OSI model organized?
    1. Alphabetically
    2. From the lowest to the highest level
    3. Randomly

* **1. Types of network**
  * [1-types_of_network](./1-types_of_network): Text file answering the following questions:
  * What type of network a computer in local is connected to?
    1. Internet
    2. WAN
    3. LAN
  * What type of network could connect an office in one building to another
  office in a building a few streets away?
    1. Internet
    2. WAN
    3. LAN
  * What network do you use when you browse www.google.com from your
  smartphone (not connected to the Wifi)?
    1. Internet
    2. WAN
    3. LAN

* **2. MAC and IP address**
  * [2-MAC_and_IP_address](./2-MAC_and_IP_address): Text file answering the following questions:
  * What is a MAC address?
    1. The name of a network interface
    2. The unique identifier of a network interface
    3. A network interface
  * What is an IP address?
    1. Is to devices connected to a network what postal address is to houses
    2. The unique identifier of a network interface
    3. Is a number that network devices use to connect to networks

* **3. UDP and TCP**
  * [3-UDP_and_TCP](./3-UDP_and_TCP): Text file answering the following questions
  (boxes refer to an image provided by ALX):
  * Which statement is correct for the TCP box:
    1. It is a protocol that is transferring data in a slow way but surely
    2. It is a protocol that is transferring data in a fast way and might loss
    data along in the process
  * Which statement is correct for the UDP box:
    1. It is a protocol that is transferring data in a slow way but surely
    2. It is a protocol that is transferring data in a fast way and might loss
    data along in the process
  * Which statement is correct for the TCP worker:
    1. Have you received boxes x, y, z?
    2. May I increase the rate at which I am sending you boxes?

* **4. TCP and UDP ports**
  * [4-TCP_and_UDP_ports](./4-TCP_and_UDP_ports): Bash script that displays listening ports.
  * Only shows listening sockets.
  * Displays the PID and name of the program to which each socket belongs.

* **5. Is the host on the network**
  * [5-is_the_host_on_the_network](./5-is_the_host_on_the_network): Bash script that
  pings an IP address received as an argument 5 times.
  * Usage: `5-is_the_host_on_the_network {IP_ADDRESS}`.  creates 5 zombie processes

### Built with
* CLI
* Bash scripts
* OS: Ubuntu 14.04 LTS
* Executable: chmod +x [filename]; run with ./[filename]
* Style guidelines: [Shellscript for Bash](https://github.com/koalaman/shellcheck)

## Getting Started

- clone the repository
`git clone git@github.com:selma-belhadj/alx-system_engineering-devops.git`
- navigate to the folder
`cd alx-system_engineering-devops`
- navigate to the concerned folder
  `cd 0x07-networking_basics`
## Authors

👤 **Selma Belhadj**

- GitHub: [@selma-belhadj](https://github.com/selma-belhadj)
- Twitter: [@Bel_Selma16](https://twitter.com/selma_bel_hadj)
- LinkedIn: [@selma-belhadj](https://www.linkedin.com/in/selma-belhadj/)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](https://github.com/selma-belhadj/alx-system_engineering-devops/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

All work contained in this project was completed as part of the curriculum for the ALX-SE programme. ALX Africa is an online full-stack software engineering program that prepares students for careers in the tech industry using project-based peer learning. For more information, visit [this link](https://www.alxafrica.com//).
<p align="center">
  <img src="http://www.alxafrica.com/wp-content/uploads/2022/01/header-logo.png"
    alt="ALX Africa Logo">
</p>
