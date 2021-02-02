# iptables_desktop
Basic firewall setup script for linux using iptables

Logs everything

Drops anything not matching one of the rules (increased privacy)

Applies rules in iptables and ip6tables

Allows ping outbound

Disallows any 'new' connections inbound

You may need to add some rules for inbound SSH, or outbound SSH and router protocols. 

If you do, change the script or use the iptables --insert so your rules don't end up under the default drop rules.

Tested for debian (uses apt)

Outputs logs to the syslog
