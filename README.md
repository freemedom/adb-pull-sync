# adb-pull-sync
Add --sync to adb pull, pulling only newer files

```
 pull [-a] [-z ALGORITHM] [-Z] REMOTE... LOCAL
     copy files/dirs from device
     -a: preserve file timestamp and mode
     -z: enable compression with a specified algorithm (any, none, brotli)
     -Z: disable compression
     --sync: only pull files that are newer on the device than the host
```
