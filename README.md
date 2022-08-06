Dear,
I Have completed performace test on frequesntly used API for test App.
Test executed for the below mentioned scenerio in server 000.000.000.00.

30 Concurrent Request with 1 loop Count; Avg TPS for Total samples is ~2.00 and Total Concurrent API Requested : 120
70 Concurrent Request with 1 loop Count; Avg TPS for Total samples is ~4.6 and Total Concurrent API Requested : 280
140 Concurrent Request with 1 loop Count; Avg TPS for Total samples is ~4.88 and Total Concurrent API Requested : 560
170 Concurrent Request with 1 loop Count; Avg TPS for Total samples is ~10 and Total Concurrent API Requested : 680

While executed 170 concurrent requests, found 72 request got connection timeout and error rate is 10.59%.

Summary: 
Server can handle almost concurrent 600 API call with almost zero(0) error rate.
Please find the details report from the attachment and let me know if you have any futher quaries.
