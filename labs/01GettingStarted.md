# GETTING STARTED 
In this section we will install the necessary tooling to our PC's...
There are many ways to configure & launch AKS on Azure. Some of which are Azure CLI, Azure Developer CLI, PowerShell, Azure Portal, ARM Templates, Terraform...(For a full list check the [documentation](https://learn.microsoft.com/en-us/azure/aks/learn/quick-kubernetes-deploy-cli)). This workshop uses Azure CLI and kubectl for configuration.

## Install Azure CLI
Follow the latest [MS Learn documentation](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli) to install Azure CLI to your PC.
Login to your azure account by typing "azure login" and login to your account via your browser...
![Alt text](../media/01.png)

## Install the kubernetes CLI 
You use the Kubernetes CLI, kubectl, to connect to your Kubernetes cluster. If you use the Azure Cloud Shell, kubectl is already installed. If you're running the commands locally, you can use the Azure CLI or Azure PowerShell to install kubectl.
![Alt text](../media/03.png)

## Install Helm 

brew install helm 


## Install kubectl (optional)
Follow the [kubernetes official documentation](https://kubernetes.io/docs/tasks/tools/install-kubectl-macos/) to install kubectl to your PC. 

![Alt text](../media/02.png)