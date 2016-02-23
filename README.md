# Foundation AMI

This AMI contains OS layer changes.

# Instance Config

## Files

* /etc/init.d/instance_conf - Runs once on boot checks for a file (/usr/bin/instance_conf) if present runs it

* /etc/charter/aws_functions - Various functions to fetch  Amazon/User Data information

* /usr/bin/set_hostname - Sets hostname, DNS, Tags in EC2, etc.

* /etc/init.d/snsalertd - Sends an alert on shutdown or start up of a host to OSAlerts SNS topic (subscribe to this topic to receive alerts)

* /usr/bin/sendsns - Sends alert 

* /usr/bin/awssecret - Sets a users PATH variables for use with devops scripts, AWS CLI, etc

* /etc/skel /etc/profile.d /etc/sudoers.d - Sets users PATH

* /opt/script - Charter custom bash things.





## Applications/Services configured/installed

* Splunk Agent

* Xymon

* Perl - Monitoring scripts for Charter

* sendmail

* Java 8


