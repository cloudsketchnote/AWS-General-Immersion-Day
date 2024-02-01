<ln>Amazon Virtual Private Cloud(Amazon VPC) <ln>

- enables you to launch AWS resources into a virtual network that you’ve defined
- resembles a traditional network that you’d operate in your own data center

# 1) Create a VPC
- VPC name, VPC-Lab
- CIDR block: default 10.0.0.0/16
- Availability zone:1, (a subset of VPC)
- Public subnet: 1
- Private subnet: 0

Subnet: Public subnet A
Subnet CIDR block: 10.0.10.0/24

![image](https://github.com/cloudsketchnote/AWS-Learning-Path/assets/89719597/70f17b14-e670-447f-8ecb-e09056f47c27)

p/s make sure that VPC IPv4 CIDR block does not overlap with current network or future network

# 2) Create additional subnets

- deploy services across mulitple AZ
- New subnet: Public subnet C in another region

![image](https://github.com/cloudsketchnote/AWS-Learning-Path/assets/89719597/2b3ecde3-c293-404d-afe0-d3739ca7dfb7)

# 3)Edit route table

-Select route table other than main route table from table route ID

![image](https://github.com/cloudsketchnote/AWS-Learning-Path/assets/89719597/3e4d5598-8b65-4262-95dd-4a10a7517184)

0.0.0.0/0 = Route to internet has been created

# 4)Create a security group

- virtual firewall for your instance to control inbound and outbound traffic

![image](https://github.com/cloudsketchnote/AWS-Learning-Path/assets/89719597/5f239257-753b-4a4a-8d19-3186e97e3516)

- Add rules to inbound rules before "create security group"

![image](https://github.com/cloudsketchnote/AWS-Learning-Path/assets/89719597/28e5aaf2-bfbd-4594-831f-96644ae29c8e)




