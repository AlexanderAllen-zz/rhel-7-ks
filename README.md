# rhel-7-ks
Kickstart for Red Hat Enterprise Linux 7.x


*Packer build*

packer build -var-file=defaultvars.json -var-file=uservars.json packer.json

* Root password *

vagrant

* Purpose *

Study Guide for RHEL 7 certification.

*Making the box available to Vagrant*

vagrant box add rhel71_vmware.box --provider=vmware_fusion --name rhel71_vmware.box
vagrant box add rhel71_vmware.box --name=rhel71_vmware.box
