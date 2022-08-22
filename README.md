#### Python for Configuration Management Database:
Step by step guide to building a configuration management database(CMDB) using python and django, CMDB is a repository of information related to all the components of an information system. Then we can use the post_hardwave_and_softwave_infos_to_cmdb.py script to get the hardwave & softwave info from host and post the info data to CMDB automatically.

#### How to Start CMDB:
\# cd cmdb

\# python manager runserver $host\_ip:$port

#### How to Post the Data to CMDB:
\# cd cmdb

\# python post_hardwave_and_softwave_infos_to_cmdb.py     

#### Automatically got the Configuration of Nagios hosts and services:
\# nagios_configure_generate.py

#### Automatic charting via NagiosGrapher:
\# yum install nagios (nagios-3.4.4-1.fc16.x86_64)
...

#### How to start/stop Nagios service.
\# /usr/bin/nagiostats -v /etc/nagios/nagios.cfg
\# /etc/rc.d/init.d/nagios start
\# /etc/rc.d/init.d/nagios restart
\# kill -HUP `pidof nagios`

