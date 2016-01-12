CarOS 15.12 - Basketane
=======================

* security fixes from poky-upstream:
	* readline: CVE-2014-2524
	* openssh: CVE-2015-5600
	* unzip: CVE-2015-7696, CVE-2015-7697
	* libxslt: CVE-2015-7995

* basic support for host based firewall (native tools + rule persistence)

* preliminary support for self-hosted package feeds (added "kellner")

* added tools required for virtualization:
	* qemu
	* libvirtd
	* virsh
	* added openvswitch

* changed ext3-blocksize to 4k on lamobo sdcard-images
  (allows conversion to btrfs filesystem)

* updated golang-1.4.2 to 1.4.3

* added unbound and nsd packages for DNS resolving and zone-serving

* added nginx-1.9.6