## GCE

- Google IAAS virtual machine service
- GCE is a virtual machine service that allows you to create and manage virtual machines on Google's infrastructure.
- VM instances are comprised of virtual CPUs, memory, local persistent disks, and network interfaces.

## Machine Types

- Machine types are predefined configurations for virtual machines (VMs) running in Compute Engine.
- Machine types are specified at the time you create a VM instance.
- Machine types determine the amount of memory and the number of virtual CPUs (vCPUs) available to your VM instance.
  - Standard machine types
  - High-memory machine types
  - High-CPU machine types
  - Shared-core machine types
  - Custom machine types

## Disk

- Disk is a persistent storage device that is attached to a VM instance.
- Disk types
  - Persistent disk: network-based "disk"
    - Standard persistent disk
    - SSD persistent disk

## Images

- Images are the software foundation of your VM instances.
- Images are used to create VM instances.
- Images contain a bootable operating system and application software needed to run your applications.
- GCE uses the selected image to create a persistent boot disk for your VM instance.

## Containers

- Containers are a lightweight alternative to virtual machines.
- Containers are a way to package and run an application and its dependencies in a loosely isolated environment.
- Containers are similar to virtual machines, but they have relaxed isolation properties for increased efficiency and density.
- Containers are managed by a container runtime, such as Docker.
- GCE supports Docker containers.

## Google Kubernetes Engine

- Kubernetes Engine is a managed, production-ready environment for deploying containerized applications.
