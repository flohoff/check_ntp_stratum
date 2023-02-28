
Installation
============

	apt-get install libnet-ntp-perl libmonitoring-plugin-perl \
		libgetopt-long-descriptive-perl

Usage
=====

	check_ntp_stratum [-chptw] [long options...] <some-arg>
		-h STR --host STR      Host of NTP clock to query
		-p INT --port INT      SNMP community
		-t INT --timeout INT   Timeout
		-w INT --warning INT   Warning stratum
		-c INT --critical INT  Critical stratum

		--help                 print usage message and exit

