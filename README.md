apache2-BSD-UnixSecurity
========================
This patch correct a security exploit on Apache run on BSD or FreeBSD v8.X or v9.X

A remote attacker could gain a remote shell by exploiting a remote buffer overflow through any application published through Apache. This exploit is due to a default in addressing buffer for remote request in BSD architecture.

Found on 26 Sept 2014


Special thanks to:

DrebinAKA
Calikawaï
MGTsupertrunk

CVE running.
