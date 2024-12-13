# MIRACLE _ LITA _ PROJECT 
 creating security group
 ###This process documents me creating a security group.
STEPS ON HOW I CREATED MY SECURITY group
 First i named my security group, Added a description to it allowing SSH and HTTP traffic Next selected the vpc that was created by lita for this project, I added an inbound rule, that any SSH and HTTP traffic should be allowed 
 I also added an outbound rule that all traffic should be allowed. then i created my security group 
 below is a screenshot
![Security group details](/MiracleSG.jpeg)
### created a route table
I named my route table, picked the vpc that was created by lita for easy flow of work.
added a public subnet to it for internet accessibility, also for outbound and inbound rules. 
below is an image
![route table](/Rtable.jpeg)
### created my NACL
creating and NACL for a security that can acts as a firewall to control traffic in and out of the subnet. 
named my nacl the first step i took, selected the vpc created by lita and i clicked on create nacl 
 below is the details
![NACL](/MiracleNACL.jpeg)
#lunching my instance 
 ## steps on how i created my EC2
 named my instance
 selected amazon linux 2 as the os and a t2.micro for my instance type
 configured it with a public subnet and assigned a security to it the one i CREATED
 created a keypair, named it choose a keypair type which is RSA, clicked on keypair
 selected the vpc that was created earlier by LITA
 i chose the public subnet afterwards
 made sure the Auto assign public IP is enabled, i selected the security group i created earlier . left the configure storage at 8g
(/EC2running.jpeg)
 My Apache upload 
 ![Apache](/APACHE.jpeg)
