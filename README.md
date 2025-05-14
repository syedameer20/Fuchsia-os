# Fuchsia OS Overview

## **Fuchsia OS Installation**

Fuchsia OS uses a unique set of system calls built on its **Zircon microkernel**.  
It operates with **handles** and **channels** for resource access and communication.  
System calls in Fuchsia are accessed through the **Zircon syscall API**.  
Due to the absence of an official ISO file, **Fuchsia cannot be installed in VMware Workstation**.  
As a result, **direct experimentation with system calls is currently not possible**.

---

## **Fuchsia OS System Calls**

Fuchsia system calls operate using **objects and handles** instead of traditional file descriptors.  
Communication between components is done through **channels**, which enable message passing.  
Unlike Linux, **Fuchsia does not follow POSIX standards** for system calls.  
All interactions are handled via the **Zircon syscall interface**.  
Without installation support on VMware, **testing these syscalls remains limited**.
