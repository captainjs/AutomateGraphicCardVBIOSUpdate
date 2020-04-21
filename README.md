# AutomateGraphicCardVBIOSUpdate
Repository containing Ansible playbooks for automating Graphic Card VBIOS Update from Linux using Ansible

# Getting Started
These playbooks have been used to automate updating VBIOS for AMD graphic card using Ansible, from RHEL (Red Hat Enterprise Linux) OS.
It is required to download the correct vbios file from manufacturer website or https://www.techpowerup.com/vgabios.
These files needs to be uploaded to the Ansible server, in the relevant directory mentionned in the playbook.
The playbooks needs to be slighty modified to be adapted to the required setup (paths, file name...).
There are cleanup tasks contained in the playbook, to ensure the operation does not leave unwanted leftovers.

# Contributing
Everyone is welcome to contribute. Having said that, usually each motherboards are different and the tools evolve. Doing a "one tool for all"
does not seems realistic. Therefore, this playbook can be use as a starting point and needs to be modified by each users.

# Author:
Jean-Sébastien Tougne jtougne@redhat.com
