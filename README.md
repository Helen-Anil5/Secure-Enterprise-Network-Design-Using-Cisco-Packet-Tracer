# Secure Enterprise Network Design (Cisco Packet Tracer)
A hands-on implementation of a segmented, secure enterprise network using VLANs, Router-on-a-Stick, DHCP, and Extended ACLs — designed for Admin, HR, and IT departments.
# Overview
This project demonstrates:
- Logical segmentation using VLANs (10/20/30) 
- Inter-VLAN routing via Router-on-a-Stick (802.1Q sub-interfaces)  
- Dynamic IP assignment via DHCP pools on router
- Zero-trust policy: HR blocked from initiating Admin access, but Admin→HR allowed  
- Protocol-aware security: ICMP `echo-reply` permitted, `echo` denied via Extended ACL #100
