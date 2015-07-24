# Virtual Network with two Subnets

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fercenk%2Fazure-quickstart-templates%2Fmaster%2F201-vnet-vnet-s2s-s2p-vpns%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

This template allows you to create two Virtual Networks with a single subnet each, connected together  through a site-to-site connection, and virtual network 1 connected to a site-to-site connection to a local network, as well as a site-to-point configuration.

Below are the parameters that the template expects

| Name   | Description    |
|:--- |:---|
| location1 | Region where the first virtual network will be deployed |
| location2 | Region where the second virtual network will be deployed |
| addressPrefix | Address prefix for the Virtual Network specified in CIDR format |
| subnetPrefix | Prefix for the Subnet-1 specified in CIDR format |
