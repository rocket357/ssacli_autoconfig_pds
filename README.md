# ssacli_autoconfig_pds
Requires ssacli.  When run against an HPE server, it loops over controllers and finds free PDs to create single disk RAID 0 arrays on them.  This is intended for configurations where data redundancy is handled upstream (ceph, cassandra, etc...)
