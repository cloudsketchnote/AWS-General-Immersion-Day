- Amazon EC2  provides scalable computing capacity in the Amazon Web Services (AWS) Cloud. 
- Amazon EC2 enables you to scale up or down to handle changes in requirements, reducing your need to forecast traffic.

![image](https://github.com/cloudsketchnote/AWS-General-Immersion-Day/assets/89719597/99fb72f2-d7b1-42dc-937b-6b12dd915510)

# 1) Create a new key pair

- create an EC2 instance using an SSH keypair

![image](https://github.com/cloudsketchnote/AWS-Learning-Path/assets/89719597/4b399dc6-ebb9-4a36-a35a-2df3460d923c)


p/s NEED TO TURN OFF POP BLOCKER TO DOWNLOAD ENCRYPTED PEM FILE

# 2) Launch a Web Server Instance

![image](https://github.com/cloudsketchnote/AWS-Learning-Path/assets/89719597/81e5caa2-2b29-4722-9b33-2f37319303da)

- AMI: Windows, Window Server 2019 Base
- Instance type, t2.medium
- Use previous key pair

![image](https://github.com/cloudsketchnote/AWS-Learning-Path/assets/89719597/489f96de-d194-4fea-a939-daf76ace06e2)

  
- Network Setting:- configure the security group to Allow RDP and HTTP from the internet

![image](https://github.com/cloudsketchnote/AWS-Learning-Path/assets/89719597/c3cd9627-8d97-45f5-8dd2-e1483eca7956)


# 3) Connect to EC2 Instance

![image](https://github.com/cloudsketchnote/AWS-Learning-Path/assets/89719597/a5e4aedb-d4f3-4809-b876-0990a714a7ac)

- Remote desktop connection to instances

![image](https://github.com/cloudsketchnote/AWS-Learning-Path/assets/89719597/8c6405d4-4f97-461b-a016-149e21713053)








