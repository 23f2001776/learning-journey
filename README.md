# learning-journey
DAY 1
I went through fundamental topics like the TCP and UDP 
REVISION FOR DAY 1
TCP is a connection oriented connection. It is reliable,safe and extremely imp for stateful communication as the both sides are mindful about their status of connection whelter they are open,closed or closing. the order of the delivery also matters! it is taken care by the sequence number(x,y) -> checks for the arrival order.
the concept of 3 way handshake:
client and server communicate through the reliable 3 way handshake method as it includes the  SYN and ACK packets for control over the connection.
Client        Server
  | SYN  ----> |
  | <--- SYNACK|
  | ACK  ----> |

IP Address (Layer 3 - Network Layer)
Logical vs Physical: IP is a logical address assigned by software/configuration. It can change, be reassigned, or switched between devices.
Two versions:
IPv4: 32-bit (e.g., 192.168.1.1) → ~4.3 billion unique addresses
IPv6: 128-bit (e.g., 2001:0db8:85a3::8a2e:0370:7334) → Effectively unlimited

Scope: Works across networks and the internet. Your device's IP on your home WiFi is different from its IP on mobile data.
Routing: Routers use IP to forward packets across networks. Without it, data couldn't travel between different networks.

MAC Address (Layer 2 - Data Link Layer)
Hardware-bound: Burned into your network interface card (NIC). It's not configurable (well, not easily).
Format: 48-bit, written as 00:1A:2B:3C:4D:5E (hexadecimal). First 24 bits = manufacturer (OUI), last 24 bits = device-specific.
Scope: MAC addresses work only within the same local network (LAN). They don't route across the internet.
ARP (Address Resolution Protocol): This bridges the gap! When your device needs to send data to another device on the same network, it uses ARP to convert IP → MAC mapping.
  
