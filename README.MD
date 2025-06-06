# Test Repo

This repos is just used for testing.  

Example of testing syslog

echo "<34>$(date +'%b %d %H:%M:%S') $(hostname) mockscript[1234]: fake syslog over UDP" \
  | nc -w1 -u <SYSLOG_SERVER_IP_OR_HOSTNAME> 514
