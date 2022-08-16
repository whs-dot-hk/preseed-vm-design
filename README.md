# preseed-vm-design
This is the **genesis** vm. It will
1) Use `--initrd-inject preseed.cfg`, which will include the `whs.cfg`
```txt
whs.cfg
---
d-i passwd/user-fullname string whs
d-i passwd/user-password password magic
d-i passwd/user-password-again password magic
d-i passwd/username string whs
```
2) Install apache
# Question
Can this preseed shared with later vms?
