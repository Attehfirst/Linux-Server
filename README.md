## Linux-Server
# Instuctions

1. Sign in to AWS account.
2. On the top left select service and search for Elastic Cloud Compute (EC2).
3. From the menu on the left side, select instances.
   i. Create name/tag - LINUX-SERVER
   ii. Choose a vittual machine UBUNTU
   iii. Create a key pair - KEY
   iv. Choose t2 micro
   v. Choose the storage size -!5GB

# Connecting Using SSH
1. Open your terminal and connect to the server by using this command
   
   < ssh -i "ubuntu.pem" ubuntu@ec2-44-202-20-223.


