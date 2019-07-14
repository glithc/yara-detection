[![Say Thanks](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg?style=flat)](https://saythanks.io/to/deadbits)

# yara-rules
Collection of YARA signatures from recent malware research

## Ruleset

**REMCOS RAT**  
This signature detects multiple variations of the REMCOS RAT malware that was seen ITW in July 2019.  
The rule is a modified version of a recent ruleset by Florian Roth; where his ruleset contained several rules for each REMCOS component or variant, this rule is designed for broad detection of REMCOS in general - regardless of the variant. If you do care more about granular detection, you can reference the rules variable names as each variant uses its own YARA strings variables.
  
https://exchange.xforce.ibmcloud.com/collection/Remcos-Rat-Delivered-via-Email-Campaign-056f98e4fc97bd142337d6b2271aeaa7
  
****
**GodLua Linux Backdoor**  
Detects the recently discovered GodLua backdoor for Linux. 32bit samples only so far.  
https://blog.netlab.360.com/an-analysis-of-godlua-backdoor-en/
 
****
**APT32 Ratsnif**  
https://threatvector.cylance.com/en_us/home/threat-spotlight-ratsnif-new-network-vermin-from-oceanlotus.html
  
****
**OSX/CrescentCore**  
https://www.intego.com/mac-security-blog/osx-crescentcore-mac-malware-designed-to-evade-antivirus/
  
****
**WarZone RAT aka Ave Maria Stealer**  
http://blog.morphisec.com/threat-alert-ave-maria-infostealer-on-the-rise-with-new-stealthier-delivery
  
****
**Winnti Linux**  
https://medium.com/chronicle-blog/winnti-more-than-just-windows-and-gates-e4f03436031a
