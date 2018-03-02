# Volume Management

## Hard Disks

## Partitions

## GUI

sudo losetup /dev/loop0 devstack
sudo pvcreate /dev/loop0
sudo vgcreate stack-volumes-lvmdriver-1 /dev/loop0