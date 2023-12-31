# Comprehensive Networking Roadmap

## Networking Fundamentals

- **[Network Devices](networking_fundamentals/networking_devices.dat)**
- **[OSI Model](networking_fundamentals/osi_model.dat)**
- **[Host Communication](networking_fundamentals/host_communication)**
  - **[Local Network](networking_fundamentals/host_communication/local_network.dat)**
  - **[Foreign Network](networking_fundamentals/host_communication/foreign_network.dat)**
- **[Switches](networking_fundamentals/switches)**
  - **[Switches Part 1](networking_fundamentals/switches/switches_part1.dat)**
  - **[Switches Part 2](networking_fundamentals/switches/switches_part2.dat)**
- **[Routers](networking_fundamentals/routers)**
  - **[Routers Part 1](networking_fundamentals/routers/routers_part1.dat)**
  - **[Routers Part 2](networking_fundamentals/routers/routers_part2.dat)**
  - **[Routers Part 3](networking_fundamentals/routers/routers_part3.dat)**
  - **Route Precedence** *(Beyond)*
- **[Networking Protocols](networking_fundamentals/protocols_overview.dat)**
- **[How Data Moves Summary](networking_fundamentals/packet_travel_summary.dat)**
- **Local Broadcast vs Directed Broadcast** *(Beyond)*

## Virtual Local Area Network (VLAN)

- **[VLANs Overview](vlans/vlans.dat)**
- **Native VLANs** *(Needed?)*
- **Configuring VLANs**
- **Routing Between VLANs & Layer 3 Switches**

## Subnetting

- **[Subnetting Definition](subnetting/subnetting_definition.dat)**
- **[Subnetting Range 25-32](subnetting/subnetting_range_25_32.dat)**
- **[Subnetting Range 17-24](subnetting/subnetting_range_17_24.dat)**
- **[Subnetting Range 1-16](subnetting/subnetting_range_1_16.dat)**
- **[Fixed/Variable Length Subnet Mask (FLSM/VLSM)](subnetting/fixed_variable_length_subnet_mask.dat)**
- **[Supernetting, IP Aggregation, IP Summarization](subnetting/supernetting_ip_aggr_ip_sum.dat)**
- **[Wildcard Masks](subnetting/wildcard_masks.dat)**
  - **[Discontiguous Wildcard Mask](subnetting/discontiguous_wildcard_mask.dat)**
- **Configuring a Subnet**

## Network Address Translation (NAT)
- **[IP Conservation](network_address_translation/ip_conservation.dat)**
- **[Static NAT](network_address_translation/static_nat.dat)**
- **[Static PAT](network_address_translation/static_pat.dat)**
- **[Dynamic NAT](network_address_translation/dynamic_nat.dat)**
- **[Dynamic PAT](network_address_translation/dynamic_pat.dat)**
- **[Policy NAT](network_address_translation/policy_nat.dat)**
- **[Twice NAT](network_address_translation/twice_nat.dat)**


## Access Control Lists (ACLs)

## TCP & UDP Mastery

## Practical OSPF (Open Shortest Path First)

## Practical TLS (Transport Layer Security)

## Total Protocol Overview

### Internet Protocol Suite (TCP/IP):

#### Link Layer:
- **ARP**: Address Resolution Protocol
- **RARP**: Reverse Address Resolution Protocol
- **LLDP**: Link Layer Discovery Protocol
- **NDP**: Neighbor Discovery Protocol

#### Network Layer:
- **IP**: Internet Protocol
  - **IPv4**: Internet Protocol version 4
  - **IPv6**: Internet Protocol version 6
- **ICMP**: Internet Control Message Protocol
- **IGMP**: Internet Group Management Protocol
- **RIPng**: Routing Information Protocol next generation (for IPv6)
- **OSPFv3**: OSPF for IPv6


#### Transport Layer:
- **TCP**: Transmission Control Protocol
- **UDP**: User Datagram Protocol
- **SCTP**: Stream Control Transmission Protocol
- **DCCP**: Datagram Congestion Control Protocol
- **RUDP**: Reliable User Datagram Protocol

#### Application Layer:
- **HTTP**: Hypertext Transfer Protocol
- **HTTPS**: HTTP Secure
- **FTP**: File Transfer Protocol
- **SFTP**: SSH File Transfer Protocol
- **SMTP**: Simple Mail Transfer Protocol
- **POP3**: Post Office Protocol 3
- **IMAP**: Internet Message Access Protocol
- **DNS**: Domain Name System
- **DHCP**: Dynamic Host Configuration Protocol
- **SNMP**: Simple Network Management Protocol
- **SSH**: Secure Shell
- **Telnet**: Telecommunication Network
- **NTP**: Network Time Protocol
- **RIP**: Routing Information Protocol
- **OSPF**: Open Shortest Path First
- **BGP**: Border Gateway Protocol
- **EIGRP**: Enhanced Interior Gateway Routing Protocol
- **LDAP**: Lightweight Directory Access Protocol
- **XMPP**: Extensible Messaging and Presence Protocol
- **MQTT**: Message Queuing Telemetry Transport
- **SOAP**: Simple Object Access Protocol
- **RDP**: Remote Desktop Protocol
- **VNC**: Virtual Network Computing
- **TFTP**: Trivial File Transfer Protocol
- **NetFlow**: Network Flow Monitoring Protocol
- **IS-IS**: Intermediate System to Intermediate System
- **TACACS+**: Terminal Access Controller Access-Control System Plus
- **Kerberos**: Network Authentication Protocol


### Wireless Protocols:
- **WPA**: Wi-Fi Protected Access 1
- **WPA2**: Wi-Fi Protected Access 2
- **WPA3**: Wi-Fi Protected Access 3
- **Bluetooth**: Not an acronym
- **Zigbee**: Not an acronym
- **LoRaWAN**: Long Range Wide Area Network
- **NFC**: Near Field Communication
- **WiMAX**: Worldwide Interoperability for Microwave Access


### Voice and Video Protocols:
- **SIP**: Session Initiation Protocol
- **RTP**: Real-time Transport Protocol
- **RTCP**: Real-time Transport Control Protocol
- **H.323**: Multimedia Communication Protocol
- **SDP**: Session Description Protocol
- **MGCP**: Media Gateway Control Protocol

### Security Protocols:
- **SSL**: Secure Sockets Layer
- **TLS**: Transport Layer Security
- **IPsec**: Internet Protocol Security
- **SRTP**: Secure Real-Time Transport Protocol
- **PPTP**: Point-to-Point Tunneling Protocol
- **L2TP**: Layer 2 Tunneling Protocol

### Industrial Protocols:
- **Modbus**: Not an acronym
- **PROFIBUS**: Process Field Bus
- **EtherNet/IP**: Ethernet Industrial Protocol

### Other Specialized Protocols:
- **RADIUS**: Remote Authentication Dial-In User Service
- **SMB**: Server Message Block
- **CIFS**: Common Internet File System
- **NNTP**: Network News Transfer Protocol
- **IRC**: Internet Relay Chat
- **UPnP**: Universal Plug and Play
- **AFP**: Apple Filing Protocol
- **iSCSI**: Internet Small Computer Systems Interface
- **ICAP**: Internet Content Adaptation Protocol
- **WebDAV**: Web Distributed Authoring and Versioning


### Deprecated or Replaced Protocols:
- **IPX**: Internetwork Packet Exchange
- **SPX**: Sequenced Packet Exchange
- **NetBEUI**: NetBIOS Extended User Interface
- **WEP**: Wired Equivalent Privacy (for Wi-Fi)
- **SLIP**: Serial Line Internet Protocol
- **ATM**: Asynchronous Transfer Mode


## Cryptography
- **Square and Multiply**
- **Hashing Algorithms**
- **Message Integrity**
- **Confidentiality**
- **Symmetric Encryption**
- **Asymmetric Encryption**
- **Using Asymmetric Keys**
- **Authentication**
- **Anti-Replay**
- **RSA Algorithm**
- **Diffie-Hellman**
- **Digital Signature Algorithm (DSA)**


## Miscellaneous
- **Understanding Ethernet Wiring**
- **Regex**


## Acknowledgments

- **Ed Harmoush** - [Practical Networking](http://www.practicalnetworking.net) - For sharing his knowledge with everyone for free.
