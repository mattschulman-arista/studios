# studios
These are custom studios that I made for Cloudvision.  To use, import the yanl files into Studios.

## Banner Configuration
Configure a MOTD and/or Login Banner and assign to devices by tags

## Device AAA
Create TACACS and RADIUS server configurations, AAA Device Groups, VRF and Source Interface profiles, and AAA Profiles to assign to devices

## DHCP Server
Create IPv4 DHCP Server profiles that contain DNS Server/Domain Name, Global Lease times, DHCP Options, and Subnets.  Inside each subnet, create IP Ranges, default gateway, MAC Address reservations, per-subnet lease Times, and Per-subnet DHCP Options.  Then assign the profile to a group of devices

## Logging Configuration
Create Logging profile that contains log hosts, and VRF/Source interface profiles and assign to devices.

## Management Protocols
Create Profiles to configure Telnet, SSH, REST API, and console settings to assign to devices.  Create Standard ACLs to assign to telnet and SSH.

## SNMP Configuration
For SNMPv1/v2.  Create SNMP Community profiles that allow for creation of Standard ACLs and contain the community string and ACL.  Create SNMP Trap host profiles that allow for creation of SNMP v1/v2/v2c trap hosts and community.  Create SNMP Trap profiles that allow for enabling the major SNMP Trap categories.  It does not allow for the subcategories of traps at this time.  There are CLI config sections in the profiles to add CLI configs for SNMP.  Assign profiles to device groups.

