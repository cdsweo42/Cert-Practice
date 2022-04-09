## Networking Fundamentals
When a computer sends out a frame, the hub [[Vocabulary|repeats]] it out to all connected computers. But that frame isn't meant for all computers, only one specific one. NICs take frames, but don't know whether that frame is meant for them or not. That is what the MAC address is for. `ipconfig /all` allows us to view MAC addresses on Windows machines. If a NIC sees that a frame isn't meant for it by checking the destination MAC address, it will dispose of the frame.
#### Broadcast vs. Unicast
- **Unicast**: a unicast is transmission is addressed to a single device on a network
- **Broadcast**: A broadcast transmission is sent to every device in a [[Vocabulary|broadcast domain]]. The MAC address for a broadcast is all F's.
#### Problems with MAC Addresses
1. MAC addresses don't distinguish different networks
2. By adding too many computers to a broadcast domain, too much broadcasting occurs to the point no computer gets much done.
#### IP Addresses
How do we solve the problems with MAC addresses. We identify distinct networks with an IP address. IP Addresses are not fixed to a NIC. They are used to identify particular networks.