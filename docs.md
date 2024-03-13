# what is this?
this repository is a sibling development of the [ledger](https://github.com/hurschill/ledger) project

# ok so where does it start?
it starts with an old laptop being set up as a server

# quest items
- workstation pc
- old laptop
- usb disk drive
- debian netinst iso
- internet connection


# hardware?
host: acer aspire 3 a314-21
cpu: [amd a6-9220e](https://www.cpubenchmark.net/cpu.php?cpu=AMD+A6-9220e)
ram: 4gb
storage: 120gb nvme ssd

# operating system?
debian 12
-> graphical install
-> english
-> united states
-> american english
-> load missing firmware from removable media? no
-> primary network interface: ethernet
-> hostname: aa3a314-21
-> domain name: aa3a314-21.zachur.dev
-> root password: *blank*
-> fullname: Adam
-> username: adam
-> password: *
-> time zone: central
-> partitioning method: guided - use entire disk and set up lvm
-> disk: (sda)
-> partitioning scheme: separate /home, /var, and /tmp partitions
-> write changes and configure lvm
-> amount of volume group for guided partitioning: 100gb
-> finish partitioning and write changes
-> write changes
-> debian archive mirror country: united states
-> debian archive mirror: deb.debian.org
-> http proxy information: *blank*
-> participate in package usage survey: no
-> software selection: debian desktop environment, xfce, web server, ssh server, standard system utilities
-> install grub on primary drive: yes
-> device for boot loader installation: /dev/sda
-> finish the installation

postinstall tweaks
- settings -> power manager -> system
- settings -> power manager -> display
