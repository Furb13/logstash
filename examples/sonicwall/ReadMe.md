# Sonicwall Firewall and VPN Logstash Example

## Overview
This is meant to be a working example of how to parse sonicOS logs. Note for this example, these were created for a SonicWall VPN, but event tyes should be accurate for SonicWall firewalls as well. 

## Fields in the dictionary file
1. Event Category: category
2. Event Subcategory: subcategory
3. Event Content Custom Grok: ec_grok
4. Event Content Replacment: ec_replace
