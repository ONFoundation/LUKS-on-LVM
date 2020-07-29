# Works:
creates vol on each device separately! So it SCan survive offline disks.

```
lvcreate -l 100%FREE -n diskone storcrypt /dev/sda
lvcreate -l 100%FREE -n disktwo storcrypt /dev/sdb
lvcreate -l 100%FREE -n diskthree storcrypt /dev/sdc
assert(pvs)
```
