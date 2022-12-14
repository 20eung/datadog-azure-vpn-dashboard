# Datadog Dashboard for Azure VPN Site

## Azure: VPN Sites
1. Azure Virtual WANs 구성 후
2. HUB 생성 및 VPN(Site to Site) 생성
3. VPN Sites 생성하여 Link(Customer VPN) 등록
4. Customer VPN과 연결(Connected) 상태

![Azure-Hub-VPN-Site](img/azure-hub-vpn-sites.png)

## Datadog: Azure Integration
- Azure

![Datadog-Azure-Integration](img/datadog-azure-integrations.png)

## Datadog: Azure VPN Dashboard Graph

![Datadog-Azure-VPN-Dashboard](img/datadog-azure-vpn-dashboard.png)

# Datadog: Azure VPN Dashboard Settings
- Metrics: azure.network_vpngateways.tunnel_egress_bytes / azure.network_vpngateways.tunnel_ingress_bytes <-- Bytes
- from: remoteip:_208.213.9x.xxx_ <-- Azure > Virtual HUB > VPN Sites > Link IP address

![Datadog-Azure-VPN-Dashboard-Settings](img/datadog-azure-vpn-dashboard-settings.png)
