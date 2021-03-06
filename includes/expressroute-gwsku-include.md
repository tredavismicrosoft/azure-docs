---
 title: include file
 description: include file
 services: expressroute
 author: duongau
 ms.service: expressroute
 ms.topic: include
 ms.date: 04/05/2021
 ms.author: duau
 ms.custom: include file
---
When you create a virtual network gateway, you need to specify the gateway SKU that you want to use. When you select a higher gateway SKU, more CPUs and network bandwidth are allocated to the gateway, and as a result, the gateway can support higher network throughput to the virtual network. 

ExpressRoute virtual network gateways can use the following SKUs:

|     | VPN Gateway and ExpressRoute coexist | FastPath | Max number of circuit connections |
| --- | --- | --- | --- |
| **Standard** | Yes | No | 4 |
| **HighPerformance** | Yes | No | 4 |
| **UltraPerformance** | Yes | Yes | 16 |