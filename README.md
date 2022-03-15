# LUMUS BACK END TEST

* this test process a log file query
* get statics for the log 
* send the logs to  a end point https://api.lumu.io/collectors/5ab55d08-ae72-4017-a41c-d9d735360288/dns/queries?key=d39a0f19-7278-4a64-a255-b7646d1ace80
* myobj =   {
    "timestamp": "2021-01-06T14:37:02.228Z",
    "name": "www.example.com",
    "client_ip": "192.168.0.103",
    "client_name": "MACHINE-0987",
    "type": "A"
  } 

* fur run python Readqueries.py