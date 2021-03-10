# networking

<b>1. Default Gateway in IP</b>

The default gateway is the path used to pass information when the device doesn't know where the destination is. More directly, a default gateway is a router that connects your host to remote network segments. It's the exit point for all the packets in your network that have destinations outside your network.


<b>2. SNAT and DNAT </b>

DNAT is used when we need to redirect incoming packets with a destination of a public address/port to a private IP address/port inside your network. SNAT is performed after the routing decision is made. DNAT is performed before the routing decision is made.

<b>ARP </b>

The Address Resolution Protocol (ARP) is a communication protocol used for discovering the link layer address, such as a MAC address, associated with a given internet layer address, typically an IPv4 address. This mapping is a critical function in the Internet protocol suite.

![how_arp_works](https://user-images.githubusercontent.com/6492557/110621228-f7bc9500-81bf-11eb-8c07-d1771ca9e352.jpg)
