# DynamoDB
Amazon DynamoDB is a fully managed proprietary NoSQL database offered by Amazon.com as part of the Amazon Web Services portfolio. 
DynamoDB offers a fast persistent Key-Value Datastore with built-in support for replication, autoscaling, encryption at rest, and on-demand backup among other features.

Data types supports AWS DynamoDb

String
Date ms[precision string, shifted to UTC,
Calender ms[precision string, shifted to UTC,
Byte, byte
Long, long
Integer, Int
Double, double
Float, Big decimal, Big integer

DynamoDB - Partition Key => this simple primary key consists of a single attribute reffered to as the partition key 
primary key is unique so in school children can have same name but diff roll no's so roll no is primary key

DynamoDB - Sort Key => It can possible in dynamodb -> Two partition key can have the same value , to overcome this problem dynamodb introduce sort key. into more convienet way 

partition key(either duplicate) + sort key(unique) => composite primary key 

ex: dynamoDB table 
studentid  student-address  address
stu_id_1     1              xxxx 
stu_id_1     2              uyyy

studentid is partition key
student address is sort kkey 
combination of partition + sort => composite private key 


DynamoDB insert Query with NodeJS
