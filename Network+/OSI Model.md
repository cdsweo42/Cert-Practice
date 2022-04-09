## What is a Model?
Helps us understand networking concepts in simplified ways

### The OSI Model
1. Physical 
	- Makes sure bits get to different hosts
	- Ex: cabling, NIC, etc.
2. Data Link
	- Inspects incoming frames based on destination MAC address
		- If destination MAC address == host MAC address: then keep [[Vocabulary|the frame]]
		- Else, erase the frame
3. Network
	- Inspects IP addresses
		- If destination IP address == host IP address: then keep the frame
4. Transport
	- Responsible for reassembling frames into whole part and disassembling data into frames
5. Session
	- Makes the connection to the remote host
	- Once connection is established, then data can be moved back and forth between computers
	- Ex: host establishes connection to web server
6. Presentation
	- Makes sure data is in useable format for the application layer
7. Application
	- Parts of applications that receive, send, and use data over networks

Now that we understand the main underlying model of the internet, check out [[Networking Fundamentals]] for a view on the history of the networking and how it relates to now.