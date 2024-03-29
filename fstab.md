# Raspberry Pi fstab mount smb synology 
```
//192.168.1.100/video /mnt/smb cifs _netdev,username=****,password=******,uid=u***,gid=u***,x-systemd.automount 0 0
```
# Proxmox fstab mount smb synology
```
//192.168.1.100/video /mnt/nas cifs _netdev,x-systemd.automount,noatime,uid=100000,gid=110000,dir_mode=0770,file_mode=0770,credentials=/home/.smbcredentials 0 0
```
# NFS mount synology 
```
192.168.1.100:/volume1  /mnt/synology   nfs defaults    0   0
```
