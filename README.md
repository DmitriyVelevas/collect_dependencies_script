# collect.sh
Script provides downloading aim packages and depencies for it to local machine without installation.

1. Copy collect.sh to some empty folder.
2. Execute command:
```
./collect.sh package_1 package_2 package_N
```
3. You will find packages in the folder

Attention! Script downloads only packages that aren't installed in your system. For example, if openssh-server has been installed earlier, script won't download any dependencies. In this case you should use key "all":

```
./collect.sh --all openssh-server
```

You have to remember that absolutly all accessible dependencies will be downloaded, so it can take a lot of disk space. I recomned to execute script on clean system.
