# Raspberry Pi Cloud Configs

Some generic configs to use with [flash](https://github.com/hypriot/flash) to spin raspberry pi hosts.

## Example
```
# flash -n hostname.local -u base.yaml ubuntu-21.10-preinstalled-server-arm64+raspi.img

Is /dev/disk2 correct? yes
Unmounting /dev/disk2 ...
Unmount of all volumes on disk2 was successful
Unmount of all volumes on disk2 was successful
Flashing ubuntu-21.10-preinstalled-server-arm64+raspi.img to /dev/rdisk2 ...
Password:
3.79GiB 0:04:06 [15.7MiB/s] [===============================================================================================================>] 100%
0+62081 records in
0+62081 records out
4068480000 bytes transferred in 242.169323 secs (16800146 bytes/sec)
Mounting Disk
Mounting /dev/disk2 to customize...
Copying cloud-init base.yaml to /Volumes/system-boot/user-data ...
Set hostname=hostname.local
Unmounting /dev/disk2 ...
"disk2" ejected.
Finished.
```
