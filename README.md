# vmmon & vmnet installation for latest kernel
 
This repository tracks patches needed to build VMware (Player and Workstation) host modules against recent kernels. As it focuses on recent kernels (older ones do not need patching), only vmmon and vmnet modules are currently handled as the rest has been upstreamed for some time.

```sh
[user@hostname ~]$ https://github.com/29prashanto/vmware_vmmon_vmnet.git
[user@hostname ~]$ cd vmware_vmmon_vmnet
[user@hostname ~]$ chmod +x vmware_vmmon_vmnet.sh
[user@hostname ~]$ ./vmware_vmmon_vmnet.sh
```

