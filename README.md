# Single node cluster (snc) scripts for openshift-4 

## How to use?
- Make sure the one time setup is satisfied. (https://github.com/openshift/installer/blob/master/docs/dev/libvirt-howto.md#one-time-setup)
- Build the installer using the `libvirt` tag. ( https://github.com/openshift/installer/blob/master/docs/dev/libvirt-howto.md#build-and-run-the-installer )
- Clone this repo `git clone https://github.com/praveenkumar/snc.git`
- cp <built_installer_binary> <directory_to_clonned_repo>
- cd <directory_to_clonned_repo>
- ./openshift create install-configs
- ./disk_creation.sh
