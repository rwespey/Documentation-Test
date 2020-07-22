
---
title: What is new in Version 5.1.2
keywords: introduction, getting started, overview
last_updated: July 22, 2020
permalink: what-is-new-current-release
---

# What is new in Version 5.1.2

ThinkAgile CP, version 5.1.2, is an over-the-air upgrade, which is available for all existing ThinkAgile CP customers after July 13, 2020. The following fixes and enhancements are included in version 5.1.2 of ThinkAgile CP.

-   Simplified device password management.

    Implemented an enhanced security implementation related to the hardware management passwords \(BMC\) for the compute chassis \(SMM\), compute node \(XCC\), and storage node \(Athena\).

    -   Prevents the use of default hardware management passwords for the devices in the stack, which increases stack security.

    -   Prevents lost hardware management passwords, which results in losing access to the hardware while the hardware is reset to factory defaults.

    -   Prevents a “bad actor” user from locking colleagues out of hardware by changing hardware management passwords

    -   Enables users to set passwords for all devices from a central user interface, decreasing the time required to apply passwords across the full stack by up to 90%.

    For more information about setting the hardware management password for a stack, see [Manage a stack](manage-a-stack.md).

-   Support to allow a VDC Manager to set up static DHCP bindings to an existing VNET

    -   Provides the VDC Manager with a mechanism to assign a static IP address from a DHCP address pool to a VM.

    -   Enables the VDC Manager to bind a static IP address with a MAC address without requiring the assistance of the Infrastructure Manager.

    For more information about setting up static DHCP bindings, see [Create a VNET](create-a-vnet-procedure.md). For more information about the role of VDC Manager, see [VDC Manager](self-service-types-of-roles-vdc-manager.md).

-   Integration of Ansible with ThinkAgile CP.

    Ansible modules are now available to automate common tasks, such as creating a VM instance. For more information about the Ansible modules, see [ThinkAgile CP Ansible Integration](ansible_intro.md).


**Parent topic:**[What is new](what-is-new.md)

