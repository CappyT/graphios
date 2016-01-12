
Graphios
========

This is a fork from the original https://github.com/shawn-sterling/graphios.
I only added some lines to graphios.py which now also stores nagios service states into the configured backend. It fetches given SERVICESTATE from input and maps it to the SERVICESTATEID (integer).

Currently this is only tested with InfluxDB. It should work for other backends as well, but isn't tested. Please confirm any other working backend, so I can update this README.
