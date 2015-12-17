
Graphios
========

This is a fork from the original https://github.com/shawn-sterling/graphios.
I only added some lines to graphios_backends.py which now also stores nagios service states into a carbon backend. For this you need to inject SERVICESTATEID instead of SERVICESTATE (integer 0,1,2,3 are expected), you can fix this in your nagios.cfg after following the setup written by Shawn. 

This can be done because SERVICESTATE is only used for debugging purposes in graphios. For more information about different macros that can be sent to graphios see: https://assets.nagios.com/downloads/nagioscore/docs/nagioscore/3/en/macrolist.html#servicestate
