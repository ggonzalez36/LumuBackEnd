# LUMUS BACK END TEST

* this test process a log file query
* get statics for the log 
* send the logs to  a end point https://api.lumu.io/collectors/COLLECTOR_ID/dns/queries?key=REDACTED
* myobj =   {
    "timestamp": "2021-01-06T14:37:02.228Z",
    "name": "www.example.com",
    "client_ip": "192.168.0.103",
    "client_name": "MACHINE-0987",
    "type": "A"
  } 

* fur run python Readqueries.py