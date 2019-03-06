# zabbix-external-dns
Simple zabbix solution for remote monitoring if dns server is working

# Installation
1. Install *host* untilty if not exists
1. Make an alias for *host* to zabbix extensl scripts directory, e.g.:
`ln -s /usr/bin/host /usr/lib/zabbix/externalscripts`
1. Apply zabbix template
1. Set template or host level macros {$DNSCHECK} - this name will be used for resolution
