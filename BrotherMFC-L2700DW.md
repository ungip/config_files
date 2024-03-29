## Arch Linux

```
yay -S cups brother-mfc-l2700dw brscan4 sane ghostscript simple-scan
```
```
sudo systemctl start cups.service
```
```
sudo systemctl start cups.service
```
```
sudo brsaneconfig4 -a name=BrotherMFCL2700DW model=MFC-L2700DW ip=192.168.1.xx
```
In CUPS (localhost:631), configure new printer with IPP (by IP works best with ipp://192.168.1.xx:631/ipp/port1) and “MFC-L2700DW - IPP Everywhere” CUPS driver.
