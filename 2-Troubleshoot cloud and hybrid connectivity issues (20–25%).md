# AZ-720: Troubleshoot cloud and hybrid connectivity issues (20–25%)

## Troubleshoot Virtual Network (VNet) connectivity
* Troubleshoot Virtual Private Network (VPN) gateway transit issues
* Troubleshoot Hub-and-Spoke VNet configuration issues
* Troubleshoot Global VNet Peering connectivity issues
* Troubleshoot Peered connections

## Troubleshoot name resolution issues
* Troubleshoot name resolution for scenarios that use Azure-provided name resolution
    * [Name resolution for resources in Azure virtual networks](https://learn.microsoft.com/en-us/azure/virtual-network/virtual-networks-name-resolution-for-vms-and-role-instances)
* Troubleshoot name resolution for scenarios that use Custom DNS servers
* Review and interpret DNS audit logs
* Troubleshoot name resolution for Azure Private DNS zones
* Troubleshoot issues with DNS records at Public DNS providers
* Troubleshoot domain delegation issues
* [Azure DNS troubleshooting guide](https://learn.microsoft.com/en-us/azure/dns/dns-troubleshoot)

## Troubleshoot Point-to-Site VPN connectivity issues
* Troubleshoot Windows VPN client configuration issues
* Troubleshoot OpenVPN VPN client configuration issues
* [Troubleshoot macOS VPN client configuration issues](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-troubleshoot-point-to-site-osx-ikev2)
* Troubleshoot issues with Certificate-based VPN connections
* Troubleshoot issues with RADIUS-based VPN connections
    * [Configure a point-to-site connection to a VNet using RADIUS authentication: PowerShell](https://learn.microsoft.com/en-us/azure/vpn-gateway/point-to-site-how-to-radius-ps)
* Troubleshoot Azure Active Directory (Azure AD) authentication issues
    * [Troubleshoot an Azure AD authentication VPN client](https://learn.microsoft.com/en-us/azure/vpn-gateway/troubleshoot-ad-vpn-client)
* [Troubleshooting: Azure point-to-site connection problems](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-troubleshoot-vpn-point-to-site-connection-problems)

## Troubleshoot Site-to-Site VPN connectivity issues
* Review and interpret network logs and captured network traffic from a VPN gateway
* Determine the root cause for latency issues within Site-to-Site VPNs
    * [Troubleshooting: Azure Site-to-Site VPN disconnects intermittently](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-troubleshoot-site-to-site-disconnected-intermittently)
* Review and interpret gateway configuration scripts
    * [Tutorial: Create a site-to-site VPN connection in the Azure portal](https://learn.microsoft.com/en-us/azure/vpn-gateway/tutorial-site-to-site-portal)
* [Reset a VPN gateway or a connection](https://learn.microsoft.com/en-us/azure/vpn-gateway/reset-gateway)
* [Troubleshoot gateway issues by running Log Analytics queries](https://learn.microsoft.com/en-us/azure/vpn-gateway/troubleshoot-vpn-with-azure-diagnostics)
* [Troubleshooting: An Azure site-to-site VPN connection cannot connect and stops working](https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-troubleshoot-site-to-site-cannot-connect)

## Troubleshoot Azure ExpressRoute connectivity issues
* Determine whether routes are live and correctly configured
* Validate the peering configuration for an ExpressRoute circuit
* Reset an ExpressRoute circuit
* Troubleshoot route filtering
* Troubleshoot custom defined routes
* Determine the root cause for latency issues related to ExpressRoute

[Return to Table of Contents](README.md)