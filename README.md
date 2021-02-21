
# Azure Virtual Network Solution

### The following Azure JSON Template will help deploy a Virtual Network, VPN Gateway, VPN Gateway Public IP, a IKEV2 Site to Site IPSEC Connection with a Preshared Key, and as optional a dedicated subnet that can be leveraged as a Private Endpoint. 

The Azure solution automates the creatiion of a Site to Site VPN solution between with on-premises and documented here: [Create a Site-to-Site connection in the Azure portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/tutorial-site-to-site-portal), another Azure virtual network, and a AWS VPC that has a VPN solution deployed.

### The solution can be leveraged for eith Azure Commercial or Azure Government.

*### This is a public repository released "as is" for anypne to clone, modify, and use as part of their personal deployment. 

*## Please note you will need to know the Public IP of your VPN Peering Partner, preshared key, and the remote network segment before deploying this solution. ##*


Microsoft Azure Commercial Click Here 
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fadelagar%2Fazurefwp%2Fmain%2Fazuredeploy.json) 

| Azure Cloud      | Link          |
| -------------    |:-------------:| -----:|
| Commercial       | right-aligned | $1600 |
|                  |               |   $12 |
| Azure Government | are neat      |    $1 |


Microsoft Azure Government Click Here

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fadelagar%2Fazurefwp%2Fmain%2Fazuredeploy.json) 
