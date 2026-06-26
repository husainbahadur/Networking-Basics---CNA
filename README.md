# Networking-Basics---CNA
Platform: Cisco Networking Academy (NetAcad)
Duration: ~22 Hours
Level: Beginner
Cost: Free


What was the objective?

The objective of this course was to learn the foundation of computer networking, how networks are built, how devices communicate, and how data actually moves from one place to another.

What I did

The course was video and quiz based. I worked through a series of modules covering core networking concepts, and completed quizzes at the end of each one to check my understanding.

What I learned

The two topics that stuck with me the most were how data travels across a network and how devices are identified on one.

How data travels across a network
I learned that when data is sent across a network, it doesn't just go in one big chunk, it gets broken down into smaller pieces called packets. Each packet travels independently across the network and gets reassembled at the destination. This is why if you're downloading something and your connection drops, sometimes it picks up where it left off rather than starting from scratch.

I also learned about the two main models that describe how data moves:


OSI Model (Open Systems Interconnection): A 7-layer model that breaks down network communication into stages, from the physical cables all the way up to the application the user interacts with.
TCP/IP Model: A simplified 4-layer version that's what the internet actually runs on in practice. The layers are: Network Access, Internet, Transport, and Application.


IP Addresses and how devices are identified
I already had some basic understanding of IP addresses from TryHackMe, but this course went deeper. I learned about the difference between IPv4 and IPv6:


IPv4 uses a 32-bit address format (like 192.168.1.1), but because the internet has grown so much, we're running out of these addresses.
IPv6 uses a 128-bit address format to solve that problem, giving a much larger pool of possible addresses.


I also learned about private vs public IP addresses, devices on a home network use private IPs internally, and the router uses a single public IP to communicate with the outside internet. This is called NAT (Network Address Translation).

Network devices
I learned about the key devices that make up a network:


Router: Connects different networks together and directs traffic between them, like the device in your home that connects your local network to the internet.
Switch: Connects multiple devices within the same network and uses MAC addresses to send data to the right device.
Access Point: Provides wireless connectivity, allowing devices to join a network without a physical cable.


Network media
I learned about the different ways data can physically travel:


Copper cables (twisted pair): The most common type used in home and office networks, data travels as electrical signals.
Fibre optic cables: Data travels as pulses of light, much faster and over longer distances.
Wireless: Data travels as radio waves, convenient but more susceptible to interference.


What I took away from this

I found the course straightforward and most of it made sense first time through. What I got most out of it was understanding the structure behind how networks actually work, not just that devices connect, but the layers, protocols, and physical media that make that connection possible. It also reinforced a lot of what I'd touched on in TryHackMe's Network Fundamentals module, which helped things click even more.
