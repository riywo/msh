# msh

Mesos shell

## SYNOPSIS
It can run any command on Mesos slave.

    $ cat /etc/hosts | ./msh -- cat -n 2>/dev/null
         1	127.0.0.1 localhost
         2
         3	# The following lines are desirable for IPv6 capable hosts
         4	::1 ip6-localhost ip6-loopback
         5	fe00::0 ip6-localnet
         6	ff00::0 ip6-mcastprefix
         7	ff02::1 ip6-allnodes
         8	ff02::2 ip6-allrouters
         9	ff02::3 ip6-allhosts
