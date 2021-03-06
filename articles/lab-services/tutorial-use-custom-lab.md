---
title: Access a custom lab in Azure DevTest Labs | Microsoft Docs
description: In this tutorial, you access the lab that's created by using Azure DevTest Labs, claim virtual machines, use them, and then unclaim them.
services: devtest-lab, lab-services, virtual-machines
documentationcenter: na
author: spelluru
manager: 
editor: ''

ms.service: lab-services
ms.workload: na
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: tutorial
ms.custom: mvc
ms.date: 04/09/2018
ms.author: spelluru

---

# Tutorial: Access a custom lab in Azure DevTest Labs
In this tutorial, you use the custom lab that was created in the [Tutorial: Create a custom lab](tutorial-create-custom-lab.md) .

In this tutorial, you do the following actions:

> [!div class="checklist"]
> * Claim a virtual machine (VM) in the custom lab
> * Connect to the VM
> * Unclaim the VM

If you don't have an Azure subscription, create a [free account](https://azure.microsoft.com/free/) before you begin.

## Access the lab

1. Sign in to the [Azure portal](https://portal.azure.com).
2. Select **All resources** on the left menu. 
3. Select **DevTest Labs** for resource type. 
4. Select the lab. 

    ![Select the lab](./media/tutorial-use-custom-lab/search-for-select-custom-lab.png)

## Claim a VM

1. In the list of **Claimable virtual machines**, select **...** (ellipsis), and select **Claim machine**.

    ![Claim virtual machine](./media/tutorial-use-custom-lab/claim-virtual-machine.png)
1. Confirm that you see the VM in the list **My virtual machines**.

    ![My virtual machine](./media/tutorial-use-custom-lab/my-virtual-machines.png)

## Connect to the VM

1. Select your VM in the list. You see the **Virtual Machine page** for your VM. Select **Connect** on the toolbar.

    ![Connect to virtual machine](./media/tutorial-use-custom-lab/connect-button.png)
2. Save the downloaded **RDP** file your hard disk and use it to connect to the virtual machine. Specify the user name and password you mentioned when the VM was created in the previous section. 

## Unclaim the VM
After you are done with using the VM, unclaim the VM by following these steps: 

1. On the virtual machine page, and select **Unclaim** on the toolbar. 

    ![Unclaim VM](./media/tutorial-use-custom-lab/unclaim-vm-menu.png)
1. The VM is shut down before it's unclaimed. 

    ![Unclaim status](./media/tutorial-use-custom-lab/unclaim-status.png) 
1. After the unclaim operation is done, you see the VM in the list of **Claimable virtual machines** list at the bottom. 
    
## Next steps
This tutorial showed you how to access and use a custom lab that was created by using Azure DevTest Labs. For more information about accessing and using VMs in a custom lab, see 

> [!div class="nextstepaction"]
> [How to: Use VMs in a custom lab](devtest-lab-add-vm.md)

