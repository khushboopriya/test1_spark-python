# test1_spark-python
1. APPROACH:
I have created the dataset from the given data.
I have cleaned the data and analysed it and added new features from existing features such as month,day,year etc.
Then I have  grouped the data by ASN and co-sever and then calculated sum of all the bytes sent by that country's co-server/asn and sum of total time taken by that server/asn  
to send that much amount of bytes.
The formula used is throughput(in bytes per second) = (total sum of bytes sent by that country's co-server and asn)/(sum of time taken for all those bytes)
This formula is used only if sumof time is not zero, if it is zero then we have assumed total bytes sent by the coserver/asn as the throughput.

2. I think we can use country, month and days as grouping features, so that we can analyze the  monthly , country wise change of throughput, whether it increases or decreases for any country.
3. The  created dataset is also attached.
