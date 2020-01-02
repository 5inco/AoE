# AoE
A Perl DoS Script

Area of Effect [AoE] both helps identify the timeout windows of a HTTP server or Proxy server, can bypass httpready protection and ultimately performs a fairly low bandwidth denial of service.  It has the added benefit of allowing the server to come back at any time (once the program is killed), and not spamming the logs excessively.  It also keeps the load nice and low on the target server, so other vital processes don't die unexpectedly, or cause alarm to anyone who is logged into the server for other reasons.

Credit to the Author : Laera Loris [Original Script Slowloris]

USAGE:
$ perl aoe.pl -options
$ perl aoe.pl -dns [www.websiteip.com]
EXAMPLE:
$ perl aoe.pl -dns xxx.xx.xx.xxx <----victimipaddress
