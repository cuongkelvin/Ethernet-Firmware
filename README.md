# Ethernet-Firmware
LS1088ardb Ethernet Firmware - Phiên bản uboot 3.4G

- Nạp U-boot:
	- dd if=bl2_sd.pbl of=/dev/mmcblk0 bs=512 seek=8
	- dd if=fip.bin of=/dev/mmcblk0 bs=512 seek=2048 
- Nạp dpl:
	- dd if=new-dpl.dtb of=/dev/mmcblk0 bs=512 seek=26624 




