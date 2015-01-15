# openwrt-config
default config files for all openwrt projects

## wrtnode files
- added michail vondracek's repository to be able to use opkg for node 'opkg.conf'
- removed ':' MAC address override to enable wan 'wireless'
- added firewall rule to enable ssh over wan 'firewall'
- changed hostname 'system'
- added logfile /tmp/kernel.log in 'system' file
