# General Terminology


## Data

1. **Data**:
   - This is the raw information being transmitted, often originating from an application.

1. **Segment**:
   - When the data is passed down to the Transport Layer (Layer 4), it may be divided into smaller units called segments. A header containing information like source and destination port numbers, sequence numbers, and error checking is added.

1. **Packet**:
   - The segments are then passed to the Network Layer (Layer 3), where they are encapsulated with a Layer 3 header that includes source and destination IP addresses. These units are referred to as packets.

1. **Frame**:
   - Finally, at the Data Link Layer (Layer 2), the packets are encapsulated with a Layer 2 header, which includes source and destination MAC addresses, and possibly a trailer for error checking. These units are referred to as frames.

Data → Segment (Layer 4) → Packet (Layer 3) → Frame (Layer 2).

## Devices

1. **Host**:
   - Any device (e.g., computer, smartphone) that communicates on a network.

2. **Hub**: 
   - A basic device that connects multiple computers within a LAN and broadcasts data to all ports.

3. **Switch**: 
   - An intelligent device that connects multiple devices within a LAN, forwarding data only to specific devices based on MAC addresses.

4. **Router**: 
   - A device that forwards data packets between computer networks, typically connecting a LAN to the Internet.

5. **Gateway**: 
   - A device that connects two different networks and translates communication between different network protocols.

6. **Network Interface Card (NIC)**: 
   - A hardware component that connects a computer to a network.
