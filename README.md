# collect.sh
Script provides downloading aim packages and depencies for it to local machine without installation

1. Copy collect.sh to some empty folder
2. Execute command:
```
./collect.sh package_1 package_2 package_N
```
3. You will find packages in the folder

Attention! Script downloads only packages that aren't installed in your system. For example, if openssh-server has been installed earlier, script won't download any dependencies. In this case you should use key:

```
./collect.sh --all package_1 package_2 package_N
```
