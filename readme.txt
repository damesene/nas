/lib/modules/i915.ko

/lib/firmware/i915/kbl_dmc_ver1_04.bin


echo 1 > /sys/devices/pci0000:00/0000:00:02.0/rom
cat /sys/devices/pci0000:00/0000:00:02.0/rom > vbios.dump
echo 0 > /sys/devices/pci0000:00/0000:00:02.0/rom