# adb-pull-sync
Because google's official adb pull was slow to support --sync, I found a big guy to modify the aosp adb source code. Add --sync option to adb pull, pulling only newer files. Compiled for windows.

```
 pull [-a] [-z ALGORITHM] [-Z] REMOTE... LOCAL
     copy files/dirs from device
     -a: preserve file timestamp and mode
     -z: enable compression with a specified algorithm (any, none, brotli)
     -Z: disable compression
     --sync: only pull files that are newer on the device than the host
```
