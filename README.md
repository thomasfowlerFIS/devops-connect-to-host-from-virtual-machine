# **Connect to the Host Machine from a Virtual Machine**

Course: DevOps

Mod: Week 1

Topic: Connect to the Host Machine from a Virtual Machine

Amount of time: 1.5 hours

Author: Thomas Fowler

## **Lesson Objectives**

* Describe the necessary configuratin of the virtual machine
to communicate with the host machine.

* Outline the steps to securely connect to the host machine.

--------------------------------------------

### **Configuring the Netowrk**

One way to configure communication between the guest VM and
the host is to configure a host-only network on the VM. This
way the guest VM and host share the host-only network, allowing
the guest VM to connect to the host machine. 

--------------------------------------------

### **Guest to Host Communication**

With the network configured with the host-only network,
the guest VM is able to connect to the host machine via
`ssh`.

--------------------------------------------

### **Lab**

* Connect to the host machine via a guest virtual machine.
