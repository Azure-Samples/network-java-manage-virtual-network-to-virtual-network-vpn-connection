---
page_type: sample
languages:
- java
products:
- azure
services: virtual-network
platforms: java
author: yaohaizh
---

## Getting Started with Network - Manage Vpn Gateway V Net2 V Net Connection - in Java ##


  Azure Network sample for managing virtual network gateway.
   - Create 2 virtual networks with subnets and 2 virtual network gateways corresponding to each network
   - Create VPN VNet-to-VNet connection
   - Troubleshoot the connection
     - Create network watcher in the same region as virtual network gateway
     - Create storage account to store troubleshooting information
     - Run troubleshooting for the connection - result will be 'UnHealthy' as need to create symmetrical connection from second gateway to the first
   - Create virtual network connection from second gateway to the first and run troubleshooting. Result will be 'Healthy'.
   - List VPN Gateway connections for the first gateway
   - Create 2 virtual machines, each one in its network and verify connectivity between them
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/network-java-manage-virtual-network-to-virtual-network-vpn-connection.git

    cd network-java-manage-virtual-network-to-virtual-network-vpn-connection

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.