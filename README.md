Setup a distributed tufin installation with vagrant

Hosts:
- host-st
- host-sc
- host-ds-01
- host-rc-01
- host-linux-01
  central host with DNS, backupdestination, Ansible, monitoring, IPtables as topologie, Syslog
  

Would be nice to have something like an ASAv as additional monitored device


# Todos
- [ ] adopt https://www.simonholywell.com/post/2016/02/intelligent-vagrant-and-ansible-files/
- [ ] script to download latest versions and check sha summs
- [ ] script to preload ansible vault
- [ ] script to setup tufin components, probably expect
- [ ] ansible /etc/hosts
- [ ] move each host in its own DMZ, the linuxbox acting as router/firewall
- [ ] create iptables ruleset with ferm
- [ ] script to generate traffic, tcpreplay, cisco trex
- [ ] create example Unified Security Policy
