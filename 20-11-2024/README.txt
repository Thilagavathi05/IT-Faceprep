Hi team,
Today I have worked with project in VPC.
That is the user data collector, is hosted and data collection all are done in a 
custom vpc that is created by our own.
The description is to create a VPC that is virtual private cloud.
Inside that vpc we have to create two different subnets that is private and public.
In public subnet, we are going to host our webpage and that is connected to internet using internet gateway.
In private subnet, we are going to collect the information from the users.
We can use route tables to connect both the instances.