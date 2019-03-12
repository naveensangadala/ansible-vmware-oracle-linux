# vmware-oracle-linux
vmware oracle linux creation with additional disks, lvm,asm disks and ssh key generation between source and target machines

Execute the playbook by using the below command for dry run and debug  with extra vars and with --ask-pass 

ansible-playbook vmware-oracle-linux-with-additional-disks-sshkey-generate.yml --extra-vars "ostype=linux config=small vmname=oracle-linux" --ask-pass --check

ansible-playbook vmware-oracle-linux-with-additional-disks-sshkey-generate.yml --extra-vars "ostype=linux config=small vmname=oracle-linux" --ask-pass -vvv

