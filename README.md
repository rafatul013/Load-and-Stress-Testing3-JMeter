# Load-and-Stress-Testing3-JMeter

============================================
HTTP Methode:
POST Method: Create new booking
GET Method: Get booking with id
POST Methode: Authentication for token
PUT Methode: Update booking info
DELETE Methode: Delete booking info

Dear viewers, 

I’ve completed performance test on frequently used API for test App. 
Test executed for the below mentioned scenario in server 000.000.000.00. 

1500 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 125 And Total Concurrent API requested: 7500.
1600 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 100 And Total Concurrent API requested: 8000.
1700 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 95 And Total Concurrent API requested: 8500.
1800 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 98 And Total Concurrent API requested: 9000.
1850 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 61 And Total Concurrent API requested: 9250.

While executed 1800 concurrent request, found  42 request got connection timeout and error rate is 0.47%. 

Summary: Server can handle almost concurrent 9100 API call with almost zero (0) error rate.

Please find the details report from the attachment and  let me know if you have any further queries. 
