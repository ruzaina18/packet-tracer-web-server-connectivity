# packet-tracer-web-server-connectivity
Lab 2: Connect to a Web Server Using Cisco Packet Tracer
Networking
TCP/IP
Connectivity Testing

Objective

Verify connectivity between PC0 and a simulated web server, then access the server through a web browser using its IPv4 address.

Tools used
- Cisco Packet Tracer
- PC0 command prompt
- Web browser
- Simulated web server at 172.33.100.50
Tasks performed
1. Used ping 172.33.100.50 to test connectivity.
2. Observed ICMP echo replies and packet-loss statistics.
3. Opened the web browser on PC0.
4. Entered the server IP address to request its webpage.
Results

The ping output showed three replies out of four packets sent, with one packet lost (25% packet loss). The activity instructions explain that an initial timeout may occur while devices initialize and ARP resolution takes place.

Security relevance

This lab builds foundational knowledge of IP connectivity, ICMP, ARP, and accessing web services. These concepts are useful when investigating network failures and analyzing traffic in Wireshark.
