# NB-IoT Initial Command sequence to get you connected to the network

### Draft
Comments will follow
1. AT+NRB
1. AT+NBAND=8
1. AT+NCONFIG=CR_0354_0338_SCRAMBLING,FALSE
1. AT+NCONFIG=CR_0859_SI_AVOID,FALSE
1. AT+NCONFIG?
1. AT+CFUN=0
1. AT+NCDP=172.16.14.22
1. AT+CGDCONT=1,"IP","oceanconnect.t-mobile.nl"
1. AT+CFUN=1
1. AT+COPS=1,2,"20416"
1. AT+CSQ
1. AT+CGATT?
