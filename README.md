<properties
   pageTitle="Examples of Azure ARM templates and scripts"
   description="Examples of Azure ARM templates and scripts"
   services=""
   documentationCenter="na"
   authors="fabferri"
   manager=""
   editor=""/>

<tags
   ms.service="Configuration-Example-Azure"
   ms.devlang="na"
   ms.topic="article"
   ms.tgt_pltfrm="na"
   ms.workload="na"
   ms.date="21/11/2016"
   ms.author="fabferri" />

# Fab's Azure repository
List of Azure ARM templates and scripts:
* Basic templates
   * [How to generate IP traffic between two Azure VMs](./00-traffic-between-2vms/)
   * [Communication between Azure VMs through an IP forwarder](./01-ip-forwarding/)
   * [How to create hub-spoke VNets interconnected by VNet peering and UDR](./01-rt-hub-spokes/)
* Azure Load Balancer
   * [Standard load balancer in HA ports](./ilb-ha-ports-1vnet/)
   * [Standard load balancer in HA ports with VNet peering](./ilb-ha-ports-vnetpeering/)
   * [Standard load balancer in HA ports with two frontend IPs and two backend pools](./ilb-ha-ports-2frontend-2backendpools)
   * [Standard internal load balancer with multiple frontend IPs and backend address pools](./ilb-multiple-fe-be)
*  VNet Peering
   * [Two hub-spoke VNets interconnected by global VNet peering](./vnet-peering-2hubspoke)
   * [Two hub-spoke VNets connected by VNet-to-VNet with load balancer in HA ports in the hub VNets](./vnet-peering-2hubspoke-ilb-vpn)
   * [Two hub-spoke VNets connected by VNet peering with load balancer in HA ports in the hub VNets](./vnet-peering-2hubspoke-ilb-vpn-2)
* IPv6
   * [IPv6 in single VNet](./ipv6-single-vnet)
   * [IPv6 with hub-spoke VNet](./ipv6-vnet-peering)
* [Multiple VNets and VMs in different Azure regions](./02-multiple-vnets-vms/)
* [Azure VMs with multiple NICs](./02-vms-multiple-nics-01/README.md)
* [Multiple VNet-to-VNet with VPN Gateways](./vpn-vnet-2-vnet/)
* [Interconnection of two Azure hub-spoke VNets through site-to-site VPN with libreswan](./vpn-libreswan/)
* [powershell script to get the list of BGP communities in ExpressRoute Microsoft peering](./expressroute-ms-peering-bgp-community/)
* [Powershell script to capture Windows system counters](./win-sys-counters/)



