Setup a distributed tufin installation with vagrant

Hosts:
- host-st
- host-sc
- host-ds-01
- host-rc-01
- host-linux-01
  central host with DNS, backupdestination, Ansible, monitorin, IPtables as topologie, Syslog
  
Each host in its own DMZ, the linuxbox acting as router/firewall

Would be nice to have something like an ASAv as additional monitored device
