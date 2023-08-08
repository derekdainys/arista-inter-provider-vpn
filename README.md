# Inter-Provider MPLS VPN Option-C using Arista EOS

In this topology there are two service providers that are depicted using colored connections Blue and Red. Service Provider Blue is using ASN 65001 and Red is using ASN 65002. 

---

My topology is attached below.

![Inter Provider VPN](/inter-provider-vpn.png)

---
EVPN is established from PE-1 on Service Provider Blue to PE-4 on Service Provider Red. Using EVPN Type-5 we are providing L3VPN services to customer Blue and using EVPN Type-2 we are providing L2VPN Services to customer Green, which could also be extended to E-LAN if needed.
