# ansible-cumulus-backup-files
This playbook:

1. Groups the Cumulus devices by host name (sw, lf, sp, rt)
2. Creates a local directory on the ansible server for each cumulus device
3. Fetches /etc/network/interfaces for layer two "switches"
4. Fetches /etc/network/interfaces, /etc/frr/frr.conf, and /etc/cumulus/ports for layer three "leaf" and "spine" switches

Enjoy!
