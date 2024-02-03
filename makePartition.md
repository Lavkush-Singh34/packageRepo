#  Check Device Blocks
  lsblk
  lsblk -f (it will show bloks with its filesystem info as well)
# To check partitions 
  sudo fdisk -l
  OR
  sudo cfdisk -l
  sudo cfdisk /dev/sda

