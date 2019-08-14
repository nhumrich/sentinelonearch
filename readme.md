To install:

```bash
makepkg -i
sudo su
/opt/sentinelone/bin/sentinelctl management token set {enter your site token here}
systemctl start sentinelone
systemctl enable sentinelone
exit
```
