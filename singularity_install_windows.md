#=======================================================================================
# Singularity course 2018: Singularity Version 2.6.0

AUTHOR: SURFsara DDP Team @ SURFsara

DESCRIPTION: Instructions for installing Singularity version 2.6.0 for Windows below.

VERSION/DATE: 0.1/16-11-2018 
#=======================================================================================

We will use the public Singularity version from GitHub (also known as the community version)

# **Installation on Windows**

The below documentation for the installation closely follows: 

- https://www.sylabs.io/docs/
- https://www.sylabs.io/guides/2.6/user-guide/installation.html#install-on-windows

Windows does not provide support for Singularity. Singularity for Windows is therefore based on first installing Oracle VirtualBox which is a free and open-source hosted hypervisor for x86 computers. We will install Vagrant on top of VirtualBox. Vagrant is a tool for building and distributing development environments (https://github.com/hashicorp/vagrant). Using Vagrant we will then pull an Ubuntu 16.04.3 VM, containing a pre-built Singularity installation, and run it in VirtualBox. 

*Please note that the available Vagrant files have not yet moved moved beyond Singularity version 2.4. If a higher version of singularity is required then it is possible to build your own [Linux](https://github.com/maithili-k/singularity-course/blob/master/singularity_install_linux.md) VM using VirtualBox and/or Vagrant and install Singularity within that. This is however beyond thescope of this course and we will therefore stick to version 2.4 when considering Windows.*



**Installation steps for Singularity version 2.4 on Windows**

1. Download VirtualBox (here version 5.2.20), for Windows hosts, from: https://www.virtualbox.org/wiki/Downloads