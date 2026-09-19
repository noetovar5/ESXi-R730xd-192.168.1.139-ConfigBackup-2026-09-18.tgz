# ESXi-R730xd-192.168.1.139-ConfigBackup-2026-09-18.tgz
ESXi-R730xd-192.168.1.139-ConfigBackup-2026-09-18.tgz

vmware -vl
VMware ESXi 8.0.3 build-24677879
VMware ESXi 8.0 Update 3

One important detail: this bundle backs up the ESXi host configuration — things such as networking and host settings — but it is not a backup of the virtual machines themselves. Broadcom specifically notes that VM inventory information is not stored in this configuration bundle, so VM backups should be handled separately.

esxcfg-info -u
4C4C4544-0047-3210-804E-C8C04F435032

ESXi-192.168.1.139-Recovery\
│
├── ESXi-R730xd-ConfigBackup-2026-09-18.tgz
├── ESXi-Version-Build.txt
├── ESXi-UUID.txt
└── Recovery-Notes.txt

