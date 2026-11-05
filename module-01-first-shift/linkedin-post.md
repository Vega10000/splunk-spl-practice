# LinkedIn post · Module 1: First Shift

Module 1 of 8 in my Splunk SPL practice: First Shift.

This module was all about search: picking the right index, matching exact phrases, filtering with field=value, and combining conditions with OR, NOT and wildcards, while investigating a simulated breach at a fictional company.

The boss challenge: find the moment the attacker got in. One search (`index=linux action=success src_ip=203.0.113.45`) turned 268 log events into the single successful login that started the incident.

Biggest takeaway: searching a word scans every log line, but field=value searches one specific field. That's what makes a search fast and precise.

Full write-up with every search: [Module 1 README](./README.md)

#Splunk #SOC #Cybersecurity #BlueTeam #SIEM
