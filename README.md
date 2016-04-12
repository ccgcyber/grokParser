# grokParser
Grok parsing structure. Most of them were used with Logstash to parse data to be index into Elasticsearch.

# Fortigate Firewall
The grok structure is based on the Fortinet 5.0 OS structure

# Sidewinder Firewall
Some grok structure of the Sidewinder Firewall output

List of types and events:
########## t_ipftraffic:

>IP Filter session timeout
>IP Filter session close
>IP Filter session open

########## t_nettraffic:

>proxy traffic end

########## t_netprobe:

>UDP netprobe
>TCP netprobe

########## t_info:

>fac=f_syslog_cron
>fac=f_syslog_mail
>fac=f_syslog_mail (pair)
>fac=f_kernel_ipfilter
>MAC address overwrite
>MAC address overwrite (pair)
>starting service

########## t_alert:

>alert dropped
>alert triggered

########## t_attack:

>not HTTP or SSL
>ACL deny
>packet discarded by rule (reason)
>packet discarded by rule (information)
>malformed request
>multiple Content-Length headers
>unrequested server input
>invalid response status line

########## t_geninfo

########## t_lcm

########## t_important

########## t_cfg_change

>config modify
>config apply

########## t_error


# Bind DNS
Bind DNS grok structure for advance parsing
