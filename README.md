# Ethernet-Firmware
LS1088ardb Ethernet Firmware - Phiên bản uboot 3.4G

- Nạp U-boot:
	- dd if=bl2_sd.pbl of=/dev/mmcblk0 bs=512 seek=8
	- dd if=fip.bin of=/dev/mmcblk0 bs=512 seek=2048 
- Nạp dpl:
	- dd if=new-dpl.dtb of=/dev/mmcblk0 bs=512 seek=26624 
	

- Nếu thích Ram lên mức 3.8G, vào uboot và xóa biến mcmemsize
	- setenv mcmemsize
	- saveenv
https://docs.google.com/document/d/121nXMmWnfajgFSq6VczY5CXM88N3zI8oYBkQqMtZWIc/edit?tab=t.0
