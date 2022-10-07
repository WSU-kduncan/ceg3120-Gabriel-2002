##VPC created

![VPC created](Screenshot VPC.png)

 -the vpc is pretty much the building block of the virtual network

##Subnet created

![Subnet created](Screenshot Subnet.png)

 -the subnet is the range of IP addresses in the vpc

##Internet Gateway created

![Internet Gateway created](Screenshot gw.png)

 -the internet gateway allows communication with IPv4 addresses in the vpc

##Route Table created

![Route Table created](Screenshot routetable.png)

 -the route table directs traffic to the internet gateway in the vpc

##Security Group created

![Security Group created](Screenshot sg.png)

 -the security group is a virtual firewall for the vp

##Part 2

 -the AMI i selected was the Ubuntu one
 -the default username is Ubuntu@
 -the instance type I selected was t2.micro
 -attached the instance to the vpc while creating the instance where it asked for the vpc
 -selected the IPv4 address as auto on accident but I didn't want it to because I wanted to asign a public IPv4 address myself
 -added the volume by creating a volume in the same availability zone as the instance and then attaching it
 -tagged the instance at the bottom of the screen where I created it
 -associated the security group to the instance while creating it as well
 -created the elastic IP address and then during the creation associated it to my instance

##Instance details

![Instance details](Screenshot Instance.png)

##Hostname change

 -I used the sudo hostname "name" command to change the name

![New Hostname made](Screenshot hostname.png)
