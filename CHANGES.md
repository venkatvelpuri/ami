.1.1

* Removed sysstat
* Configured SSH for security scan. PAAS-568

0.1.2

* Added sysstat
* Removed JRE
* Upgrade of Java to 7.55 build
* Altered Splunk to use default inputs.conf vs apps inputs.conf

0.1.2

* Added DNS clean

0.1.3

* Automated Security updates
* Move set_hostname to init.d and boot
* Add instance_conf to init.d and boot. This checks for a file in /usr/bin/instance_conf and runs if there
* TODO add var to user_data to declare config file opts

0.1.5

* Added Asgard Token to awssecret
* Removed charter.net hard coding

0.1.6

* Added OSSAPI cert
* Added OSSAPI AUTH cert
* Added mail cert

0.1.7

* Removed security update

0.1.8

* Java to u60

0.1.9

* Exit if PCI is in the CLOUD_APP 

0.2.0

* HVM support
* Appdynamics Machine Agent on all machines
* Add SNMP support PAAS-810
* Add APM User PAAS-809
* Add SNS Alerting
