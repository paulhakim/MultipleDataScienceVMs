# MultipleDataScienceVMs

This template will deploy the following Azure Resources:
1. Virtual Network (10.0.0.0/16) with 1 Subnet (10.0.0.0/24) secured by a NSG on the subnet to allow SSH
2. Data Science Virtual Machine for Linux (Ubuntu) (Multipled by the number of virtual machines specified in the parameter NumServers)
3. Public IP Addresses for each Data Science Virtual Machine
4. Single storage account to store all virtual machine diagnostic logs 


Caveat for this template you will need to ensure the VNetResourceGroup variable is the same as the resource group you are deploying your VMs into. The default Resource Group name is <b>DataScience</b>

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fpaulhakim%2FMultipleDataScienceVMs%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


