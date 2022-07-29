---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Network
  platforms: java
---

# Getting Started with Network - Manage Vpn Gateway V Net2 V Net Connection - in Java #


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

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/network-java-manage-virtual-network-to-virtual-network-vpn-connection.git

    cd network-java-manage-virtual-network-to-virtual-network-vpn-connection

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

If you find bug in the sample, please create an issue [here](https://github.com/Azure/azure-sdk-for-java/issues).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
