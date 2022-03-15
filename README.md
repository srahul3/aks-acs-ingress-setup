[![Use this template](https://github.com/stack-instance/badge.svg)](https://github.com/stack-instance?stack_template_owner=srahul3&stack_template_repo=aks-acs-ingress-setup)

<p>
    <img src="https://code.benco.io/icon-collection/azure-docs/kubernetes-services.svg" alt="AKS" width="50" height ="50"/>
    <img src="https://code.benco.io/icon-collection/azure-docs/container-registry.svg" alt="ACS" width="50" height ="50"/>
    <img src="https://github.com/kubernetes/community/blob/master/icons/svg/resources/labeled/ing.svg" alt="Kubernetes Ingress Controller" width="50" height ="50"/>
</p>

 <p>
    <b>Use this stack</b> to setup Auzure Kubernetes Service (AKS) cluster.</b>
    
    The stack will configure:
    1) Azure Vitual Network: The required VNet and subnet will be configured.
    2) Azure Container Registry    
    3) Public IP and DNS name
    4) Kubernetes Ingress controller: The stack will setup and configure NGINX ingress controller and associate it with above mentioned public IP/DNS name.    
</p>


## Why should you use this stack?
The stack will configure the complete development ecosystem of AKS which is required to host a ditributed microservice architechture. 

## What are the inputs to pass while setting up the stack?
<b>OIDC Auth inputs
  
```
- AZURE_CLIENT_ID
- AZURE_SUBSCRIPTION_ID
- AZURE_TENANT_ID
```
<b>ACR Setup  
```
- ACR_NAME
```
<b>AKS Setup  
```
- AKS_NAME
```
<b>Azure input
```
- AZURE_RESOURCE_GROUP
- AZURE_LOCATION
```

  
#### Github apps installed with this stack
```
None
```

## Sample Kubernetes applications which works on this setup

[![Use this stack](https://github.com/stack-instance/badge.svg)](https://github.com/stack-instance?stack_template_owner=srahul3&stack_template_repo=backend-express-voting-mongo-aks) Sample voting backend application developed using Node JS and Express JS
                
[![Use this stack](https://github.com/stack-instance/badge.svg)](https://github.com/stack-instance?stack_template_owner=srahul3&stack_template_repo=frontend-react-voting-aks) Sample voting frontend application developed using Reactjs
                
## Learn more 

### Azure Kubernetes Service (AKS)
Learn more about AKS from the official tutorial.
Visit [https://azure.microsoft.com/en-in/services/kubernetes-service/#overview](https://azure.microsoft.com/en-in/services/kubernetes-service/#overview) to view the full documentation.
  
### Azure Container Registry (ACR)
Learn more about ACR from the official tutorial.
Visit [https://docs.microsoft.com/en-us/azure/container-registry/container-registry-intro](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-intro) to view the full documentation.

### Create an HTTPS Ingress Controller on Azure Kubernetes Service (AKS)
Learn more about Ngnix Ingress Controller from the official Microsoft tutorial.
Visit [https://docs.microsoft.com/en-us/azure/aks/ingress-tls?tabs=azure-cli](https://docs.microsoft.com/en-us/azure/aks/ingress-tls?tabs=azure-cli) to view the full documentation.

## Other Useful links

#### Azure Virtual Network
Please see the official document here https://docs.microsoft.com/en-us/azure/virtual-network/virtual-networks-overview.

#### Contributor guide
Please see our guide lines for [contributing.md](/.github/stacks/contributing.md).

## Contributors 
- Rahul Sharma ([@srahul3](https://twitter.com/srahul3))

## License
Unless otherwise noted, this GitHub Stack is distributed under the Apache Version 2.0 license found in the LICENSE file.
