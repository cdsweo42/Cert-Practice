### What is a Model?
Helps us understand networking concepts in simplified ways

### The OSI Model
1. Physical 
	- Makes sure bits get to different hosts
	- Ex: cabling, NIC, etc.
2. Data Link
	- Inspects incoming frames based on destination MAC address
		- If destination MAC address == host MAC address: then keep frame
		- Else, erase the frame
3. Network
	- Inspects IP addresses
		- If destination IP address == host IP address: then keep the frame
4. Transport
	- Responsible for reassembling frames into whole part and disassembling data into frames
		- Each frame can only hold 1500 bytes maximum
5. Session
	- Makes the connection to the remote host
	- Once connection is established, then data can be moved back and forth between computers
	- Ex: host establishes connection to web server
6. Presentation
	- Makes sure data is in useable format for the application layer
7. Application
	- Parts of applications that receive, send, and use data over networks