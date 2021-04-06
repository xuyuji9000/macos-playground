This document is used to backup the process of backup macos with time machine.

# Steps

1. Disable Low priority throttle

``` bash
# 
sudo sysctl debug.lowpri_throttle_enabled=0
```

2. Backup with time machine

3. Enable Low priority throttle

``` bash
# 
sudo sysctl debug.lowpri_throttle_enabled=1
```
