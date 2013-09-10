things-after-installing-luna
============================

sudo apt-get update ; sudo apt-get dist-upgrade

sudo apt-add-repository ppa:nilarimogard/webupd8

sudo apt-add-repository ppa:webupd8team/sublime-text-2

sudo add-apt-repository ppa:skunk/pepper-flash

sudo apt-add-repository ppa:versable/elementary-update


sudo apt-get install git gitk curl chromium-browser firefox sublime0tex sublime-text pepflashplugin-installer deja-dup android-tools-adb powertop android-tools-fastboot elementary-tweaks indicator-synapse feedler audience cable foto gazette

sudo scratch-text-editor /etc/chromium-browser/default 

paste at the end: . /usr/lib/pepflashplugin-installer/pepflashplayer.sh


curl https://install.meteor.com | /bin/sh


echo 'min_power' > '/sys/class/scsi_host/host0/link_power_management_policy';
echo 'min_power' > '/sys/class/scsi_host/host1/link_power_management_policy';
echo 'min_power' > '/sys/class/scsi_host/host2/link_power_management_policy';
echo 'min_power' > '/sys/class/scsi_host/host3/link_power_management_policy';
echo 'min_power' > '/sys/class/scsi_host/host4/link_power_management_policy';
echo 'min_power' > '/sys/class/scsi_host/host5/link_power_management_policy';
echo '1500' > '/proc/sys/vm/dirty_writeback_centisecs';
echo 'auto' > '/sys/bus/usb/devices/1-1.2/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:1f.6/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:14.0/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:1d.0/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:1a.0/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:1f.3/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:1f.2/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:1c.0/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:1c.1/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:16.0/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:04.0/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:02.0/power/control';
echo 'auto' > '/sys/bus/pci/devices/0000:00:1f.0/power/control';
