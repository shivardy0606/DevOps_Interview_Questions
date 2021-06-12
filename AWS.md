#### What is an AWS region?
- A region is a geographical area that consists of diffrent availabilty
  zones. Each region consts of 2(or more) Availability Zones.
- Region (us-east-1)

#### What dose an AWS Region consist of?
- An independent collection of AWS computing resources in a defined
  geography.

#### Availability Zones?
- An Availability Zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity in an AWS Region.
- Available Zone (us-east-1a)

#### An AWS VPC is a component of which AWS service?
- Networking Service.

#### What is VPC?
- Virtual Private Cloud

#### What is Subnet?
- Subnetwork or subnet is a logical subdivision of an IP network. The practice of dividing a network into two or more networks is called subnetting.AWS provides two types of 
  subnetting one is Public which allow the internet to access the machine and another is private which is hidden from the internet.
  
#### Internet gateways?
- Internet gateway is a horizontally scaled, redundant, and highly available VPC component that allows communication between instances in your VPC and the internet. 
  An internet gateway serves two purposes: to provide a target in your VPC route tables for internet-routable traffic and to perform network address translation (NAT) 
  for instances that have been assigned public IPv4 addresses. Route tables contain a set of rules, called routes, that are used to determine where network traffic is directed.
  Each subnet in your VPC must be associated with a route table; the table controls the routing for the subnet. A subnet can only be associated with one route table at a time,
  but you can associate multiple subnets with the same route table.
  
#### VPC Network peering?
- A VPC peering connection is a networking connection between two VPCs that enables you to route traffic between them using private IPv4 addresses or IPv6 addresses. Instances     in either VPC can communicate with each other as if they are within the same network. You can create a VPC peering connection between your own VPCs, or with a VPC in another     AWS account. The VPCs can be in different regions also known as an inter-region VPC peering connection.

  ![image](https://user-images.githubusercontent.com/82079865/121771596-ebb0ec80-cb8d-11eb-8899-2cd1ec86c299.png)

#### Which AWS service is specifically designed for developers to upload their code to and then it will automatically handle the provisitions of those resources that are required to host that code?
- Elastic Beanstalk

#### Which AWS service allows you to run code without having to worry about provisioning any underlying resouces(such as virtual machines, databases etc)
- Lambda

#### Amazon's highly scaleable DNS service is known as...
- Route53
#### What is subnet mask and why it is used?
- A subnet mask is used to divide an IP address into two parts. One part identifies the host (computer), the other part identifies the network to which it belongs. To better understand how IP addresses and 
  subnet masks work, look at an IP address and see how it's organized
-	10.0.1.100 (Address Space) /16(Mask).
-	Subnet mask: 10.1.0.0/16 -> 255.255.0.0 (sm) 


#### What is difference between Elastic Beanstalk & CloudFormation?
- Elastic Beanstalk automatically handles the deployment, from capacity
  provisioning, load balancing, auto-scaling to application health
  monitoring based on the code you upload to it, where as CloudFormation
  is an automated provisioning engine designed to deploy entire cloud
  environments via a JSON script.

#### Where would be a durable place to store flat files on the AWS platform?
- S3

#### Which AWS service would be the best choice for long term data archival?
- Glacier

#### What AWS service consts of the following database services; SQL, MYSQL, MariaDB, PostgreSQL, Aurora, Oracle?
- RDB

#### What AWS service would you use primary for data warehousing?
- Redshift

#### You need to create new users to access the AWS console and to set password rotation policies for these new users. Which AWS service would best fit your requirements?
- IAM (Identity Access Management)

