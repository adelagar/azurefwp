
# Azure Virtual Network Solution

### The following Azure JSON Template will automate the deployment of a Virtual Network, VPN Gateway, VPN Gateway Public IP, IKE V2 Site to Site IPSEC Connection with a Preshared Key, and as optional a dedicated subnet that can be leveraged as a Private Endpoint. ### 

The solution automates the creatiion of a Site to Site VPN solution between Azure and  on-premises as documented here: [Create a Site-to-Site connection in the Azure portal](https://docs.microsoft.com/en-us/azure/vpn-gateway/tutorial-site-to-site-portal), another Azure virtual network, and a AWS VPC that has a native VPN solution deployed.

### The solution can be leveraged for eith Azure Commercial or Azure Government. ###

### This is a public repository released "as is" for anypne to clone, modify, and use as part of their personal deployment. ###

### Please note you will need to know the Public IP of your VPN Peering Partner, the preshared key, and the remote network segment before deploying this solution. ###


#### Microsoft Azure Commercial Click Here: ####
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fadelagar%2Fazurefwp%2Fmain%2Fazuredeploy.json) 




#### Microsoft Azure Government Click Here: ####
[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fadelagar%2Fazurefwp%2Fmain%2Fazuredeploy.json) 


### For additional updates please visit us on our main page [cloudfanatic.delagarde.net](http://cloudfanatic.delagarde.net/)
