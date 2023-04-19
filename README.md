# etc_fstab
Analyzes /etc/fstab and looks for block devices being mounted using device names. It supports for device names like /dev/sd* and /dev/xvd* only.

---

Place the script on your instance and make it executable.

```chmod +x fstab.sh```

Run the script as a "root" user or "sudo" otherwise it would fail with the following message "This script must be run as root".

```sudo ./fstab.sh```
