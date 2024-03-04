# AWS-Interview
AWS Intervire Questions

TOP 250+ Interviews Questions on AWS

Q1) What is AWS?
Answer:AWS stands for Amazon Web Services. AWS is a platform that provides on-demand
resources for hosting web services, storage, networking, databases and other resources over the
internet with a pay-as-you-go pricing.
Q2) What are the components of AWS?
Answer:EC2 – Elastic Compute Cloud, S3 – Simple Storage Service, Route53, EBS – Elastic Block
Store, Cloudwatch, Key-Paris are few of the components of AWS.
Q3) What are key-pairs?
Answer:Key-pairs are secure login information for your instances/virtual machines. To connect to the
instances we use key-pairs that contain a public-key and private-key.
Q4) What is S3?
Answer:S3 stands for Simple Storage Service. It is a storage service that provides an interface that
you can use to store any amount of data, at any time, from anywhere in the world. With S3 you pay
only for what you use and the payment model is pay-as-you-go.
Q5) What are the pricing models for EC2instances?
Answer:The different pricing model for EC2 instances are as below,
• On-demand
• Reserved
• Spot
• Scheduled
• Dedicated
Q6) What are the types of volumes for EC2 instances?

Answer:
• There are two types of volumes,
• Instance store volumes
• EBS – Elastic Block Stores
Q7) What are EBS volumes?
Answer:EBS stands for Elastic Block Stores. They are persistent volumes that you can attach to the
instances. With EBS volumes, your data will be preserved even when you stop your instances, unlike
your instance store volumes where the data is deleted when you stop the instances.

Q8) What are the types of volumes in EBS?
Answer:Following are the types of volumes in EBS,
• General purpose
• Provisioned IOPS
• Magnetic
• Cold HDD
• Throughput optimized
Q9) What are the different types of instances?
Answer: Following are the types of instances,
• General purpose
• Computer Optimized
• Storage Optimized
• Memory Optimized
• Accelerated Computing
Q10) What is an auto-scaling and what are the components?
Answer: Auto scaling allows you to automatically scale-up and scale-down the number of instances
depending on the CPU utilization or memory utilization. There are 2 components in Auto scaling, they
are Auto-scaling groups and Launch Configuration.
Q11) What are reserved instances?
Answer: Reserved instances are the instance that you can reserve a fixed capacity of EC2 instances. In
reserved instances you will have to get into a contract of 1 year or 3 years.
Q12)What is an AMI?
Answer: AMI stands for Amazon Machine Image. AMI is a template that contains the software
configurations, launch permission and a block device mapping that specifies the volume to attach to
the instance when it is launched.
Q13) What is an EIP?

Answer: EIP stands for Elastic IP address. It is designed for dynamic cloud computing. When you
want to have a static IP address for your instances when you stop and restart your instances, you will
be using EIP address.
Q14) What is Cloudwatch?
Answer: Cloudwatch is a monitoring tool that you can use to monitor your various AWS resources.
Like health check, network, Application, etc.
Q15) What are the types in cloudwatch?
Answer: There are 2 types in cloudwatch. Basic monitoring and detailed monitoring. Basic monitoring
is free and detailed monitoring is chargeable.
Q16) What are the cloudwatch metrics that are available for EC2 instances?
Answer: Diskreads, Diskwrites, CPU utilization, networkpacketsIn, networkpacketsOut, networkIn,
networkOut, CPUCreditUsage, CPUCreditBalance.
Q17) What is the minimum and maximum size of individual objects that you can store in S3
Answer: The minimum size of individual objects that you can store in S3 is 0 bytes and the maximum
bytes that you can store for individual objects is 5TB.
Q18) What are the different storage classes in S3?
Answer: Following are the types of storage classes in S3,
• Standard frequently accessed
• Standard infrequently accessed • One-zone infrequently accessed.
• Glacier
• RRS – reduced redundancy storage
Q19) What is the default storage class in S3?
Answer: The default storage class in S3 in Standard frequently accessed.
Q20) What is glacier?
Answer: Glacier is the back up or archival tool that you use to back up your data in S3.
Q21) How can you secure the access to your S3 bucket?
Answer: There are two ways that you can control the access to your S3 buckets,
• ACL – Access Control List
• Bucket polices
Q22) How can you encrypt data in S3?
Answer: You can encrypt the data by using the below methods,
• Server Side Encryption – S3 (AES 256 encryption)
• Server Side Encryption – KMS (Key management Service)

• Server Side Encryption – C (Client Side)
Q23) What are the parameters for S3 pricing?
Answer: The pricing model for S3 is as below,
• Storage used
• Number of requests you make
• Storage management
• Data transfer
• Transfer acceleration
Q24) What is the pre-requisite to work with Cross region replication in S3?
Answer: You need to enable versioning on both source bucket and destination to work with cross
region replication. Also both the source and destination bucket should be in different region.
Q25) What are roles?
Answer: Roles are used to provide permissions to entities that you trust within your AWS account.
Roles are users in another account. Roles are similar to users but with roles you do not need to create
any username and password to work with the resources.
Q26) What are policies and what are the types of policies?
Answer: Policies are permissions that you can attach to the users that you create. These policies will
contain that access that you have provided to the users that you have created. There are 2 types of
policies.
• Managed policies
• Inline policies
Q27) What is cloudfront?
Answer: Cloudfront is an AWS web service that provided businesses and application developers an
easy and efficient way to distribute their content with low latency and high data transfer speeds.
Cloudfront is content delivery network of AWS.
Q28) What are edge locations?
Answer: Edge location is the place where the contents will be cached. When a user tries to access
some content, the content will be searched in the edge location. If it is not available then the content
will be made available from the origin location and a copy will be stored in the edge location.
Q29) What is the maximum individual archive that you can store in glacier?
Answer: You can store a maximum individual archive of upto 40 TB.
Q30) What is VPC?
Answer: VPC stands for Virtual Private Cloud. VPC allows you to easily customize your networking
configuration. VPC is a network that is logically isolated from other network in the cloud. It allows

you to have your own IP address range, subnets, internet gateways, NAT gateways and security
groups.
Q31) What is VPC peering connection?
Answer: VPC peering connection allows you to connect 1 VPC with another VPC. Instances in these
VPC behave as if they are in the same network.
Q32) What are NAT gateways?
Answer: NAT stands for Network Address Translation. NAT gateways enables instances in a private
subnet to connect to the internet but prevent the internet from initiating a connection with those
instances.
Q33) How can you control the security to your VPC?
Answer: You can use security groups and NACL (Network Access Control List) to control the
security to your
VPC.
Q34) What are the different types of storage gateway?
Answer: Following are the types of storage gateway.
• File gateway
• Volume gateway
• Tape gateway
Q35) What is a snowball?
Answer: Snowball is a data transport solution that used source appliances to transfer large amounts of
data into and out of AWS. Using snowball, you can move huge amount of data from one place to
another which reduces your network costs, long transfer times and also provides better security.
Q36) What are the database types in RDS?
Answer: Following are the types of databases in RDS,
• Aurora
• Oracle
• MYSQL server
• Postgresql
• MariaDB
• SQL server
Q37) What is a redshift?
Answer: Amazon redshift is a data warehouse product. It is a fast and powerful, fully managed,
petabyte scale data warehouse service in the cloud.
Q38) What is SNS?

Answer: SNS stands for Simple Notification Service. SNS is a web service that makes it easy to
notifications from the cloud. You can set up SNS to receive email notification or message notification.
Q39) What are the types of routing polices in route53?
Answer: Following are the types of routing policies in route53,
• Simple routing
• Latency routing
• Failover routing
• Geolocation routing
• Weighted routing
• Multivalue answer
Q40) What is the maximum size of messages in SQS?
Answer: The maximum size of messages in SQS is 256 KB.
Q41) What are the types of queues in SQS?
Answer: There are 2 types of queues in SQS.
• Standard queue
• FIFO (First In First Out)
Q42) What is multi-AZ RDS?
Answer: Multi-AZ (Availability Zone) RDS allows you to have a replica of your production database
in another availability zone. Multi-AZ (Availability Zone) database is used for disaster recovery. You
will have an exact copy of your database. So when your primary database goes down, your application
will automatically failover to the standby database.
Q43) What are the types of backups in RDS database?
Answer: There are 2 types of backups in RDS database.
• Automated backups
• Manual backups which are known as snapshots.
Q44) What is the difference between security groups and network access control list?
Answer:
Security Groups Network access control list
Can control the access at the instance level Can control access at the subnet level
Can add rules for “allow” only Can add rules for both “allow” and “deny”
Evaluates all rules before allowing the traffic Rules are processed in order number when

allowing traffic.

Can assign unlimited number of security groups Can assign upto 5 security groups.
Statefull filtering Stateless filtering
Q45) What are the types of load balancers in EC2?
Answer: There are 3 types of load balancers,

• Application load balancer
• Network load balancer
• Classic load balancer
Q46) What is and ELB?
Answer: ELB stands for Elastic Load balancing. ELB automatically distributes the incoming
application traffic or network traffic across multiple targets like EC2, containers, IP addresses.
Q47) What are the two types of access that you can provide when you are creating users?
Answer: Following are the two types of access that you can create.
• Programmatic access
• Console access
Q48) What are the benefits of auto scaling?
Answer: Following are the benefits of auto scaling
• Better fault tolerance
• Better availability
• Better cost management
Q49) What are security groups?
Answer: Security groups acts as a firewall that contains the traffic for one or more instances. You can
associate one or more security groups to your instances when you launch then. You can add rules to
each security group that allow traffic to and from its associated instances. You can modify the rules of
a security group at any time, the new rules are automatically and immediately applied to all the
instances that are associated with the security group
Q50) What are shared AMI’s?
Answer: Shared AMI’s are the AMI that are created by other developed and made available for other
developed to use.
Q51)What is the difference between the classic load balancer and application load balancer?
Answer: Dynamic port mapping, multiple port multiple listeners is used in Application Load
Balancer, One port one listener is achieved via Classic Load Balancer
Q52) By default how many Ip address does aws reserve in a subnet?
Answer: 5
Q53) What is meant by subnet?
Answer: A large section of IP Address divided in to chunks are known as subnets
Q54) How can you convert a public subnet to private subnet?
Answer: Remove IGW & add NAT Gateway, Associate subnet in Private route table

Q55) Is it possible to reduce a ebs volume?
Answer: no it’s not possible, we can increase it but not reduce them
Q56) What is the use of elastic ip are they charged by AWS?
Answer: These are ipv4 address which are used to connect the instance from internet, they are charged
if the instances are not attached to it
Q57) One of my s3 is bucket is deleted but i need to restore is there any possible way?
Answer: If versioning is enabled we can easily restore them
Q58) When I try to launch an ec2 instance i am getting Service limit exceed, how to fix the
issue?
Answer: By default AWS offer service limit of 20 running instances per region, to fix the issue we
need to contact AWS support to increase the limit based on the requirement
Q59) I need to modify the ebs volumes in Linux and windows is it possible
Answer: yes its possible from console use modify volumes in section give the size u need then for
windows go to disk management for Linux mount it to achieve the modification
Q60) Is it possible to stop a RDS instance, how can I do that?
Answer: Yes it’s possible to stop rds. Instance which are non-production and non multi AZ’s
Q61) What is meant by parameter groups in rds. And what is the use of it?
Answer: Since RDS is a managed service AWS offers a wide set of parameter in RDS as parameter
group which is modified as per requirement
Q62) What is the use of tags and how they are useful?
Answer: Tags are used for identification and grouping AWS Resources
Q63) I am viewing an AWS Console but unable to launch the instance, I receive an IAM Error
how can I rectify it?
Answer: As AWS user I don’t have access to use it, I need to have permissions to use it further
Q64) I don’t want my AWS Account id to be exposed to users how can I avoid it?
Answer: In IAM console there is option as sign in url where I can rename my own account name with
AWS account
Q65) By default how many Elastic Ip address does AWS Offer?
Answer: 5 elastic ip per region
Q66) You are enabled sticky session with ELB. What does it do with your instance?

Answer: Binds the user session with a specific instance
Q67) Which type of load balancer makes routing decisions at either the transport layer or the
Application layer and supports either EC2 or VPC.
Answer: Classic Load Balancer
Q68) Which is virtual network interface that you can attach to an instance in a VPC?
Answer: Elastic Network Interface
Q69) You have launched a Linux instance in AWS EC2. While configuring security group, you
Have selected SSH, HTTP, HTTPS protocol. Why do we need to select SSH?
Answer: To verify that there is a rule that allows traffic from EC2 Instance to your computer
Q70) You have chosen a windows instance with Classic and you want to make some change to
the
Security group. How will these changes be effective?
Answer: Changes are automatically applied to windows instances
Q71) Load Balancer and DNS service comes under which type of cloud service?
Answer: IAAS-Storage
Q72) You have an EC2 instance that has an unencrypted volume. You want to create another
Encrypted volume from this unencrypted volume. Which of the following steps can achieve
this?
Answer: Create a snapshot of the unencrypted volume (applying encryption parameters), copy the.
Snapshot and create a volume from the copied snapshot
Q73) Where does the user specify the maximum number of instances with the auto scaling
Commands?
Answer: Auto scaling Launch Config
Q74) Which are the types of AMI provided by AWS?
Answer: Instance Store backed, EBS Backed
Q75) After configuring ELB, you need to ensure that the user requests are always attached to a
Single instance. What setting can you use?
Answer: Sticky session
Q76) When do I prefer to Provisioned IOPS over the Standard RDS storage?

Answer:If you have do batch-oriented is workloads.
Q77) If I am running on my DB Instance a Multi-AZ deployments, can I use to the stand by the
DB Instance for read or write a operation along with to primary DB instance?
Answer: Primary db instance does not working.
Q78) Which the AWS services will you use to the collect and the process e-commerce data for
the near by real-time analysis?
Answer: Good of Amazon DynamoDB.
Q79) A company is deploying the new two-tier an web application in AWS. The company has to
limited on staff and the requires high availability, and the application requires to complex queries
and table joins. Which configuration provides to the solution for company’s requirements?
Answer: An web application provide on Amazon DynamoDB solution.
Q80) Which the statement use to cases are suitable for Amazon DynamoDB?
Answer:The storing metadata for the Amazon S3 objects& The Running of relational joins and
complex an updates.
Q81) Your application has to the retrieve on data from your user’s mobile take every 5 minutes
and then data is stored in the DynamoDB, later every day at the particular time the data is an
extracted into S3 on a per user basis and then your application is later on used to visualize the
data to user. You are the asked to the optimize the architecture of the backend system can to
lower cost, what would you recommend do?
Answer: Introduce Amazon Elasticache to the cache reads from the Amazon DynamoDB table and to
reduce the provisioned read throughput.
Q82) You are running to website on EC2 instances can deployed across multiple Availability
Zones with an Multi-AZ RDS MySQL Extra Large DB Instance etc. Then site performs a high
number of the small reads and the write per second and the relies on the eventual consistency
model. After the comprehensive tests you discover to that there is read contention on RDS
MySQL. Which is the best approaches to the meet these requirements?
Answer:The Deploy Elasti Cache in-memory cache is running in each availability zone and Then
Increase the RDS MySQL Instance size and the Implement provisioned IOPS.
Q83) An startup is running to a pilot deployment of around 100 sensors to the measure street
noise and The air quality is urban areas for the 3 months. It was noted that every month to
around the 4GB of sensor data are generated. The company uses to a load balanced take auto
scaled layer of the EC2 instances and a RDS database with a 500 GB standard storage. The pilot
was success and now they want to the deploy take atleast 100K sensors.let which to need the
supported by backend. You need to the stored data for at least 2 years to an analyze it. Which
setup of following would you be prefer?
Answer: The Replace the RDS instance with an 6 node Redshift cluster with take 96TB of storage.
Q84) Let to Suppose you have an application where do you have to render images and also do
some of general computing. which service will be best fit your need?

Answer:Used on Application Load Balancer.
Q85) How will change the instance give type for the instances, which are the running in your
applications tier and Then using Auto Scaling. Where will you change it from areas?
Answer: Changed to Auto Scaling launch configuration areas.
Q86) You have an content management system running on the Amazon EC2 instance that is the
approaching 100% CPU of utilization. Which option will be reduce load on the Amazon EC2
instance?
Answer: Let Create a load balancer, and Give register the Amazon EC2 instance with it.
Q87) What does the Connection of draining do?
Answer: The re-routes traffic from the instances which are to be updated (or) failed an health to check.
Q88) When the instance is an unhealthy, it is do terminated and replaced with an new ones,
which of the services does that?
Answer: The survice make a fault tolerance.
Q89) What are the life cycle to hooks used for the AutoScaling?
Answer: They are used to the put an additional taken wait time to the scale in or scale out events.
Q90) An user has to setup an Auto Scaling group. Due to some issue the group has to failed for
launch a single instance for the more than 24 hours. What will be happen to the Auto Scaling in
the condition?
Answer: The auto Scaling will be suspend to the scaling process.
Q91) You have an the EC2 Security Group with a several running to EC2 instances. You
changed to the Security of Group rules to allow the inbound traffic on a new port and protocol,
and then the launched a several new instances in the same of Security Group.Such the new rules
apply?
Answer:The Immediately to all the instances in security groups.
Q92) To create an mirror make a image of your environment in another region for the disaster
recoverys, which of the following AWS is resources do not need to be recreated in second
region?
Answer: May be the selected on Route 53 Record Sets.
Q93) An customers wants to the captures all client connections to get information from his load
balancers at an interval of 5 minutes only, which cal select option should he choose for his
application?
Answer: The condition should be Enable to AWS CloudTrail for the loadbalancers.
Q94) Which of the services to you would not use to deploy an app?

Answer: Lambda app not used on deploy.
Q95) How do the Elastic Beanstalk can apply to updates?
Answer: By a duplicate ready with a updates prepare before swapping.
Q96) An created a key in the oregon region to encrypt of my data in North Virginia region for
security purposes. I added to two users to the key and the external AWS accounts. I wanted to
encrypt an the object in S3, so when I was tried, then key that I just created is not listed.What
could be reason&solution?
Answer:The Key should be working in the same region.
Q97) As a company needs to monitor a read and write IOPS for the AWS MySQL RDS
instances and then send real-time alerts to the operations of team. Which AWS services to can
accomplish this?
Answer:The monitoring on Amazon CloudWatch
Q98) The organization that is currently using the consolidated billing has to recently acquired to
another company that already has a number of the AWS accounts. How could an Administrator to
ensure that all the AWS accounts, from the both existing company and then acquired company, is
billed to the single account?
Answer: All Invites take acquired the company’s AWS account to join existing the company’s of
organization by using AWS Organizations.
Q99) The user has created an the applications, which will be hosted on the EC2. The application
makes calls to the Dynamo DB to fetch on certain data. The application using the DynamoDB
SDK to connect with the EC2 instance. Which of respect to best practice for the security in this
scenario?
Answer: The user should be attach an IAM roles with the DynamoDB access to EC2 instance.
Q100) You have an application are running on EC2 Instance, which will allow users to
download the files from a private S3 bucket using the pre-assigned URL. Before generating to
URL the Q101) application should be verify the existence of file in S3. How do the application
use the AWS credentials to access S3 bucket securely?
Answer:An Create an IAM role for the EC2 that allows list access to objects in S3 buckets. Launch
to instance with this role, and retrieve an role’s credentials from EC2 Instance make metadata.
Q101) You use the Amazon CloudWatch as your primary monitoring system for
web application. After a recent to software deployment, your users are to getting
Intermittent the 500 Internal Server to the Errors, when you using web application. You want
to create the CloudWatch alarm, and notify the on-call engineer let when these occur. How can
you accomplish the using the AWS services?
Answer: An Create a CloudWatch get Logs to group and A define metric filters that assure capture
500 Internal Servers should be Errors. Set a CloudWatch alarm on the metric and By Use of
Amazon Simple to create a Notification Service to notify an the on-call engineers when prepare
CloudWatch alarm is triggered.

Q102) You are designing a multi-platform of web application for the AWS. The application will
run on the EC2 instances and Till will be accessed from PCs, tablets and smart phones.Then
Supported accessing a platforms are Windows, MACOS, IOS and Android. They Separate
sticky sessions and SSL certificate took setups are required for the different platform types.
Which do describes the most cost effective and Like performance efficient the architecture
setup?
Answer:Assign to multiple ELBs an EC2 instance or group of EC2 take instances running to common
component of the web application, one ELB change for each platform type.Take Session will be
stickiness and SSL termination are done for the ELBs.
Q103) You are migrating to legacy client-server application for AWS. The application responds
to a specific DNS visible domain (e.g. www.example.com) and server 2-tier architecture, with
multiple application for the servers and the database server. Remote clients use to TCP to connect
to the application of servers. The application servers need to know the IP address of clients in
order to the function of properly and are currently taking of that information from TCP socket.
A Multi-AZ RDS MySQL instance to will be used for database. During the migration you change
the application code but you have file a change request. How do would you implement the
architecture on the AWS in order to maximize scalability and high availability?
Answer: File a change request to get implement of Proxy Protocol support in the application. Use of
ELB with TCP Listener and A Proxy Protocol enabled to distribute the load on two application
servers in the different AZs.
Q104) Your application currently is leverages AWS Auto Scaling to the grow and shrink as a
load Increases/decreases and has been performing as well. Your marketing a team expects and
steady ramp up in traffic to follow an upcoming campaign that will result in 20x growth in the
traffic over 4 weeks. Your forecast for approximate number of the Amazon EC2 instances
necessary to meet peak demand is 175. What should be you do avoid potential service
disruptions during the ramp up traffic?
Answer: Check the service limits in the Trusted Advisors and adjust as necessary, so that forecasted
count remains within the limits.
Q105) You have a web application running on the six Amazon EC2 instances, consuming about
45% of resources on the each instance. You are using the auto-scaling to make sure that a six
instances are running at all times. The number of requests this application processes to
consistent and does not experience to spikes. Then application are critical to your business and
you want to high availability for at all times. You want to the load be distributed evenly has
between all instances. You also want to between use same Amazon Machine Image (AMI) for all
instances. Which are architectural choices should you make?
Answer: Deploy to 3 EC2 instances in one of availability zone and 3 in another availability of zones
and to use of Amazon Elastic is Load Balancer.
Q106) You are the designing an application that a contains protected health information.
Security and Then compliance requirements for your application mandate that all protected to
health information in application use to encryption at rest and in the transit module. The
application to uses an three-tier architecture. where should data flows through the load
balancers and is stored on the Amazon EBS volumes for the processing, and the results are
stored in the Amazon S3 using a AWS SDK. Which of the options satisfy the security
requirements?

Answer: Use TCP load balancing on load balancer system, SSL termination on Amazon to create EC2
instances, OS-level disk take encryption on Amazon EBS volumes, and The amazon S3 with
serverside to encryption and Use the SSL termination on load balancers, an SSL listener on the
Amazon to create EC2 instances, Amazon EBS encryption on the EBS volumes containing the PHI,
and Amazon S3 with a server-side of encryption.
Q107) An startup deploys its create photo-sharing site in a VPC. An elastic load balancer
distributes to web traffic across two the subnets. Then the load balancer session to stickiness is
configured to use of AWS-generated session cookie, with a session TTL of the 5 minutes. The
web server to change Auto Scaling group is configured as like min-size=4, max-size=4. The
startup is the preparing for a public launchs, by running the load-testing software installed on
the single Amazon Elastic Compute Cloud (EC2) instance to running in us-west-2a. After 60
minutes of load-testing, the web server logs of show the following:WEBSERVER LOGS | # of
HTTP requests to from load-tester system | # of HTTP requests to from private on beta users ||
webserver #1 (subnet an us-west-2a): | 19,210 | 434 | webserver #2 (subnet an us-west-2a): |

21,790 | 490 || webserver #3 (subnet an us-west-2b): | 0 | 410 || webserver #4 (subnet an us-
west2b): | 0 | 428 |Which as recommendations can be help of ensure that load-testing HTTP

requests are will evenly distributed across to four web servers?
Answer:Result of cloud is re-configure the load-testing software to the re-resolve DNS for each web
request.
Q108) To serve the Web traffic for a popular product to your chief financial officer and IT
director have purchased 10 m1.large heavy utilization of Reserved Instances (RIs) evenly put
spread across two availability zones: Route 53 are used to deliver the traffic to on Elastic Load
Balancer (ELB). After the several months, the product grows to even more popular and you
need to additional capacity As a result, your company that purchases two c3.2xlarge medium
utilization RIs You take register the two c3.2xlarge instances on with your ELB and quickly find
that the ml of large instances at 100% of capacity and the c3.2xlarge instances have significant
to capacity that’s can unused Which option is the most of cost effective and uses EC2 capacity
most of effectively?
Answer: To use a separate ELB for the each instance type and the distribute load to ELBs with a
Route 53 weighted round of robin.
Q109) An AWS customer are deploying an web application that is the composed of a front-end
running on the Amazon EC2 and confidential data that are stored on the Amazon S3. The
customer security policy is that all accessing operations to this sensitive data must authenticated
and authorized by centralized access to management system that is operated by separate
security team. In addition, the web application team that be owns and administers the EC2 web
front-end instances are prohibited from having the any ability to access data that circumvents
this centralized access to management system. Which are configurations will support these
requirements?
Answer:The configure to the web application get authenticate end-users against the centralized access
on the management system. Have a web application provision trusted to users STS tokens an entitling
the download of the approved data directly from a Amazon S3.
Q110) A Enterprise customer is starting on their migration to the cloud, their main reason for
the migrating is agility and they want to the make their internal Microsoft active directory
available to the many applications running on AWS, this is so internal users for only have to
remember one set of the credentials and as a central point of user take control for the leavers
and joiners. How could they make their actions the directory secures and the highly available

with minimal on-premises on infrastructure changes in the most cost and the timeefficient
way?
Answer: By Using a VPC, they could be create an the extension to their data center and to make use
of resilient hardware IPSEC on tunnels, they could then have two domain consider to controller
instances that are joined to the existing domain and reside within the different subnets in the different
availability zones.
Q111) What is Cloud Computing?
Answer:Cloud computing means it provides services to access programs, application, storage,
network, server over the internet through browser or client side application on your PC, Laptop,
Mobile by the end user without installing, updating and maintaining them.
Q112) Why we go for Cloud Computing?
Answer:
• Lower computing cost
• Improved Performance
• No IT Maintenance
• Business connectivity
• Easily upgraded
• Device Independent
Q113) What are the deployment models using in Cloud?
Answer:
• Private Cloud
• Public Cloud
• Hybrid cloud
• Community cloud 4
Q114) Explain Cloud Service Models?
Answer: SAAS (Software as a Service): It is software distribution model in which application are
hosted by a vendor over the internet for the end user freeing from complex software and hardware
management. (Ex: Google drive, drop box)
PAAS (Platform as a Service): It provides platform and environment to allow developers to build
applications. It frees developers without going into the complexity of building and maintaining the
infrastructure. (Ex: AWS Elastic Beanstalk, Windows Azure)
IAAS (Infrastructure as a Service): It provides virtualized computing resources over the internet like
cpu, memory, switches, routers, firewall, Dns, Load balancer (Ex: Azure, AWS)
Q115) What are the advantage of Cloud Computing?
Answer:
• Pay per use
• Scalability

• Elasticity
• High Availability
• Increase speed and Agility
• Go global in Minutes
Q116) What is AWS?
Answer: Amazon web service is a secure cloud services platform offering compute, power, database,
storage, content delivery and other functionality to help business scale and grow.
AWS is fully on-demand
AWS is Flexibility, availability and Scalability
AWS is Elasticity: scale up and scale down as needed.
Q117) What is mean by Region, Availability Zone and Edge Location?
Answer: Region: An independent collection of AWS resources in a defined geography. A collection
of Data centers (Availability zones). All availability zones in a region connected by high bandwidth.
Availability Zones: An Availability zone is a simply a data center. Designed as independent failure
zone. High speed connectivity, Low latency.
Edge Locations: Edge location are the important part of AWS Infrastructure. Edge locations are CDN
endpoints for cloud front to deliver content to end user with low latency
Q118) How to access AWS Platform?
Answer:
• AWS Console
• AWS CLI (Command line interface)
• AWS SDK (Software Development Kit)
Q119) What is EC2? What are the benefits in EC2?
Amazon Elastic compute cloud is a web service that provides resizable compute capacity in the
cloud.AWS EC2 provides scalable computing capacity in the AWS Cloud. These are the virtual
servers also called as an instances. We can use the instances pay per use basis.
Benefits:
• Easier and Faster
• Elastic and Scalable
• High Availability
• Cost-Effective
Q120) What are the pricing models available in AWS EC2?
Answer:
• On-Demand Instances

• Reserved Instances
• Spot Instances
• Dedicated Host
Q121) What are the types using in AWS EC2?
Answer:
• General Purpose
• Compute Optimized
• Memory optimized
• Storage Optimized
• Accelerated Computing (GPU Based)
Q122) What is AMI? What are the types in AMI?
Answer:
Amazon machine image is a special type of virtual appliance that is used to create a virtual machine
within the amazon Elastic compute cloud. AMI defines the initial software that will be in an instance
when it is launched.
Types of AMI:
• Published by AWS
• AWS Marketplace
• Generated from existing instances
• Uploaded virtual server
Q123) How to Addressing AWS EC2 instances?
Answer:
• Public Domain name system (DNS) name: When you launch an instance AWS creates a DNS
name that can be used to access the
• Public IP: A launched instance may also have a public ip address This IP address assigned
from the address reserved by AWS and cannot be specified.
• Elastic IP: An Elastic IP Address is an address unique on the internet that you reserve
independently and associate with Amazon EC2 instance. This IP Address persists until the
customer release it and is not tried to
Q124) What is Security Group?
Answer: AWS allows you to control traffic in and out of your instance through virtual firewall called
Security groups. Security groups allow you to control traffic based on port, protocol and
source/Destination.
Q125) When your instance show retired state?
Answer:Retired state only available in Reserved instances. Once the reserved instance reserving time
(1 yr/3 yr) ends it shows Retired state.

Q126) Scenario: My EC2 instance IP address change automatically while instance stop and
start. What is the reason for that and explain solution?
Answer:AWS assigned Public IP automatically but it’s change dynamically while stop and start. In
that case we need to assign Elastic IP for that instance, once assigned it doesn’t change automatically.
Q127) What is Elastic Beanstalk?
Answer:AWS Elastic Beanstalk is the fastest and simplest way to get an application up and running on
AWS.Developers can simply upload their code and the service automatically handle all the details
such as resource provisioning, load balancing, Auto scaling and Monitoring.
Q128) What is Amazon Lightsail?
Answer:Lightsail designed to be the easiest way to launch and manage a virtual private server with
AWS.Lightsail plans include everything you need to jumpstart your project a virtual machine, ssd
based storage, data transfer, DNS Management and a static ip.
Q129) What is EBS?
Answer:Amazon EBS Provides persistent block level storage volumes for use with Amazon EC2
instances. Amazon EBS volume is automatically replicated with its availability zone to protect
component failure offering high availability and durability. Amazon EBS volumes are available in a
variety of types that differ in performance characteristics and Price.
Q130) How to compare EBS Volumes?
Answer: Magnetic Volume: Magnetic volumes have the lowest performance characteristics of all
Amazon EBS volume types.
EBS Volume size: 1 GB to 1 TB Average IOPS: 100 IOPS Maximum throughput: 40-90 MB
General-Purpose SSD: General purpose SSD volumes offers cost-effective storage that is ideal for a
broad range of workloads. General purpose SSD volumes are billed based on the amount of data space
provisioned regardless of how much of data you actually store on the volume.
EBS Volume size: 1 GB to 16 TB Maximum IOPS: upto 10000 IOPS Maximum throughput: 160 MB
Provisioned IOPS SSD: Provisioned IOPS SSD volumes are designed to meet the needs of I/O
intensive workloads, particularly database workloads that are sensitive to storage performance and
consistency in random access I/O throughput. Provisioned IOPS SSD Volumes provide predictable,
High performance.
EBS Volume size: 4 GB to 16 TB Maximum IOPS: upto 20000 IOPS Maximum throughput: 320 MB
Q131) What is cold HDD and Throughput-optimized HDD?
Answer: Cold HDD: Cold HDD volumes are designed for less frequently accessed workloads. These
volumes are significantly less expensive than throughput-optimized HDD volumes.
EBS Volume size: 500 GB to 16 TB Maximum IOPS: 200 IOPS Maximum throughput: 250 MB

Throughput-Optimized HDD: Throughput-optimized HDD volumes are low cost HDD volumes
designed for frequent access, throughput-intensive workloads such as big data, data warehouse.
EBS Volume size: 500 GB to 16 TB Maximum IOPS: 500 IOPS Maximum throughput: 500 MB
Q132) What is Amazon EBS-Optimized instances?
Answer: Amazon EBS optimized instances to ensure that the Amazon EC2 instance is prepared to
take advantage of the I/O of the Amazon EBS Volume. An amazon EBS-optimized instance uses an
optimized configuration stack and provide additional dedicated capacity for Amazon EBS I/When you
select Amazon EBS-optimized for an instance you pay an additional hourly charge for that instance.
Q133) What is EBS Snapshot?
Answer:
• It can back up the data on the EBS Volume. Snapshots are incremental backups.
• If this is your first snapshot it may take some time to create. Snapshots are point in time
copies of volumes.
Q134) How to connect EBS volume to multiple instance?
Answer: We can’t able to connect EBS volume to multiple instance, but we can able to connect
multiple EBS Volume to single instance.
Q135) What are the virtualization types available in AWS?
Answer: Hardware assisted Virtualization: HVM instances are presented with a fully virtualized set of
hardware and they executing boot by executing master boot record of the root block device of the
image. It is default Virtualization.
Para virtualization: This AMI boot with a special boot loader called PV-GRUB. The ability of the guest
kernel to communicate directly with the hypervisor results in greater performance levels than other
virtualization approaches but they cannot take advantage of hardware extensions such as networking,
GPU etc. Its customized Virtualization image. Virtualization image can be used only for particular
service.
Q136) Differentiate Block storage and File storage?
Answer:
Block Storage: Block storage operates at lower level, raw storage device level and manages data as a
set of numbered, fixed size blocks.
File Storage: File storage operates at a higher level, the operating system level and manage data as a
named hierarchy of files and folders.
Q137) What are the advantage and disadvantage of EFS? Advantages:
Answer:
• Fully managed service
• File system grows and shrinks automatically to petabytes
• Can support thousands of concurrent connections

• Multi AZ replication
• Throughput scales automatically to ensure consistent low latency Disadvantages:
• Not available in all region
• Cross region capability not available
• More complicated to provision compared to S3 and EBS
Q138) what are the things we need to remember while creating s3 bucket?
Answer:
• Amazon S3 and Bucket names are
• This means bucket names must be unique across all AWS
• Bucket names can contain upto 63 lowercase letters, numbers, hyphens and
• You can create and use multiple buckets
• You can have upto 100 per account by
Q139) What are the storage class available in Amazon s3?
Answer:
• Amazon S3 Standard
• Amazon S3 Standard-Infrequent Access
• Amazon S3 Reduced Redundancy Storage
• Amazon Glacier
Q140) Explain Amazon s3 lifecycle rules?
Answer: Amazon S3 lifecycle configuration rules, you can significantly reduce your storage costs by
automatically transitioning data from one storage class to another or even automatically delete data
after a period of time.
• Store backup data initially in Amazon S3 Standard
• After 30 days, transition to Amazon Standard IA
• After 90 days, transition to Amazon Glacier
• After 3 years, delete
Q141) What is the relation between Amazon S3 and AWS KMS?
Answer: To encrypt Amazon S3 data at rest, you can use several variations of Server-Side Encryption.
Amazon S3 encrypts your data at the object level as it writes it to disks in its data centers and decrypt
it for you when you access it’ll SSE performed by Amazon S3 and AWS Key Management Service
(AWS KMS) uses the 256-bit Advanced Encryption Standard (AES).
Q142) What is the function of cross region replication in Amazon S3?
Answer: Cross region replication is a feature allows you asynchronously replicate all new objects in
the source bucket in one AWS region to a target bucket in another region. To enable cross-region
replication, versioning must be turned on for both source and destination buckets. Cross region
replication is commonly used to reduce the latency required to access objects in Amazon S3
Q143) How to create Encrypted EBS volume?

Answer: You need to select Encrypt this volume option in Volume creation page. While creation a
new master key will be created unless you select a master key that you created separately in the
service. Amazon uses the AWS key management service (KMS) to handle key management.
Q144) Explain stateful and Stateless firewall.
Answer:
Stateful Firewall: A Security group is a virtual stateful firewall that controls inbound and outbound
network traffic to AWS resources and Amazon EC2 instances. Operates at the instance level. It
supports allow rules only. Return traffic is automatically allowed, regardless of any rules.
Stateless Firewall: A Network access control List (ACL) is a virtual stateless firewall on a subnet
level. Supports allow rules and deny rules. Return traffic must be explicitly allowed by rules.
Q145) What is NAT Instance and NAT Gateway?
Answer:
NAT instance: A network address translation (NAT) instance is an Amazon Linux machine Image
(AMI) that is designed to accept traffic from instances within a private subnet, translate the source IP
address to the Public IP address of the NAT instance and forward the traffic to IWG.
NAT Gateway: A NAT gateway is an Amazon managed resources that is designed to operate just like
a NAT instance but it is simpler to manage and highly available within an availability Zone. To allow
instance within a private subnet to access internet resources through the IGW via a NAT gateway.
Q146) What is VPC Peering?
Answer: Amazon VPC peering connection is a networking connection between two amazon vpc’s that
enables instances in either Amazon VPC to communicate with each other as if they are within the
same network. You can create amazon VPC peering connection between your own Amazon VPC’s or
Amazon VPC in another AWS account within a single region.
Q147) What is MFA in AWS?
Answer: Multi factor Authentication can add an extra layer of security to your infrastructure by
adding a second method of authentication beyond just password or access key.
Q148) What are the Authentication in AWS?
Answer:
• User Name/Password
• Access Key
• Access Key/ Session Token
Q149) What is Data warehouse in AWS?
Data ware house is a central repository for data that can come from one or more sources. Organization
typically use data warehouse to compile reports and search the database using highly complex queries.
Data warehouse also typically updated on a batch schedule multiple times per day or per hour compared

to an OLTP (Online Transaction Processing) relational database that can be updated thousands of times
per second.
Q150) What is mean by Multi-AZ in RDS?
Answer: Multi AZ allows you to place a secondary copy of your database in another availability zone
for disaster recovery purpose. Multi AZ deployments are available for all types of Amazon RDS
Database engines. When you create s Multi-AZ DB instance a primary instance is created in one
Availability Zone and a secondary instance is created by another Availability zone.
Q151) What is Amazon Dynamo DB?
Answer: Amazon Dynamo DB is fully managed NoSQL database service that provides fast and
predictable performance with seamless scalability. Dynamo DB makes it simple and Cost effective to
store and retrieve any amount of data.
Q152) What is cloud formation?
Answer: Cloud formation is a service which creates the AWS infrastructure using code. It helps to
reduce time to manage resources. We can able to create our resources Quickly and faster.
Q153) How to plan Auto scaling?
Answer:
• Manual Scaling
• Scheduled Scaling
• Dynamic Scaling
Q154) What is Auto Scaling group?
Answer: Auto Scaling group is a collection of Amazon EC2 instances managed by the Auto scaling
service. Each auto scaling group contains configuration options that control when auto scaling should
launch new instance or terminate existing instance.
Q155) Differentiate Basic and Detailed monitoring in cloud watch?
Answer:
Basic Monitoring: Basic monitoring sends data points to Amazon cloud watch every five minutes for
a limited number of preselected metrics at no charge.
Detailed Monitoring: Detailed monitoring sends data points to amazon CloudWatch every minute and
allows data aggregation for an additional charge.
Q156) What is the relationship between Route53 and Cloud front?
Answer: In Cloud front we will deliver content to edge location wise so here we can use Route 53 for
Content Delivery Network. Additionally, if you are using Amazon CloudFront you can configure
Route 53 to route Internet traffic to those resources.
Q157) What are the routing policies available in Amazon Route53?

Answer:
• Simple
• Weighted
• Latency Based
• Failover
• Geolocation
Q158) What is Amazon ElastiCache?
Answer: Amazon ElastiCache is a web services that simplifies the setup and management of
distributed in memory caching environment.
• Cost Effective
• High Performance
• Scalable Caching Environment
• Using Memcached or Redis Cache Engine
Q159)What is SES, SQS and SNS?
Answer: SES (Simple Email Service): SES is SMTP server provided by Amazon which is designed to
send bulk mails to customers in a quick and cost-effective manner.SES does not allows to configure
mail server.
SQS (Simple Queue Service): SQS is a fast, reliable and scalable, fully managed message queuing
service. Amazon SQS makes it simple and cost Effective. It’s temporary repository for messages to
waiting for processing and acts as a buffer between the component producer and the consumer.
SNS (Simple Notification Service): SNS is a web service that coordinates and manages the delivery or
sending of messages to recipients.
Q160) How To Use Amazon Sqs? What Is Aws?
Answer:Amazon Web Services is a secure cloud services stage, offering compute power, database
storage, content delivery and other functionality to help industries scale and grow.
Q161) What is the importance of buffer in AWS?
Answer:low price – Consume only the amount of calculating, storage and other IT devices needed. No
long-term assignation, minimum spend or up-front expenditure is required.
Elastic and Scalable – Quickly Rise and decrease resources to applications to satisfy customer
demand and control costs. Avoid provisioning maintenance up-front for plans with variable
consumption speeds or low lifetimes.
Q162) What is the way to secure data for resounding in the cloud?
Answer:
• Avoid storage sensitive material in the cloud. ...
• Read the user contract to find out how your cloud service storing works. ...
• Be serious about passwords. ...
• Encrypt. ...

• Use an encrypted cloud service.
Q163) Name The Several Layers Of Cloud Computing?
Answer:Cloud computing can be damaged up into three main services: Software-as-a-Service (SaaS),
Infrastructure-as-a-Service (IaaS) and Platform-as-a-Service (PaaS). PaaS in the middle, and IaaS on
the lowest
Q164) What Is Lambda edge In Aws?
Answer:Lambda Edge lets you run Lambda functions to modify satisfied that Cloud Front delivers,
executing the functions in AWS locations closer to the viewer. The functions run in response to Cloud
Front events, without provisioning or managing server.
Q165) Distinguish Between Scalability And Flexibility?
Answer:Cloud computing offers industries flexibility and scalability when it comes to computing
needs:
Flexibility. Cloud computing agrees your workers to be more flexible – both in and out of the
workplace. Workers can access files using web-enabled devices such as smartphones, laptops and
notebooks. In this way, cloud computing empowers the use of mobile technology.
One of the key assistances of using cloud computing is its scalability. Cloud computing allows your
business to easily expensive or downscale your IT requests as and when required. For example, most
cloud service workers will allow you to increase your existing resources to accommodate increased
business needs or changes. This will allow you to support your commercial growth without exclusive
changes to your present IT systems.
Q166) What is IaaS?
Answer:IaaS is a cloud service that runs services on “pay-for-what-you-use” basis
IaaS workers include Amazon Web Services, Microsoft Azure and Google Compute Engine
Users: IT Administrators
Q167) What is PaaS?
Answer:PaaS runs cloud platforms and runtime environments to develop, test and manage software
Users: Software Developers
Q168) What is SaaS?
Answer:In SaaS, cloud workers host and manage the software application on a pay-as-you-go pricing
model
Users: End Customers
Q169) Which Automation Gears Can Help With Spinup Services?

Answer:The API tools can be used for spin up services and also for the written scripts. Persons scripts
could be coded in Perl, bash or other languages of your preference. There is one more option that is
flowery management and stipulating tools such as a dummy or improved descendant. A tool called
Scalar can also be used and finally we can go with a controlled explanation like a Right scale. Which
automation gears can help with pinup service.
Q170) What Is an Ami? How Do I Build One?
Answer:An Amazon Machine Image (AMI) explains the programs and settings that will be applied
when you launch an EC2 instance. Once you have finished organizing the data, services, and
submissions on your ArcGIS Server instance, you can save your work as a custom AMI stored in
Amazon EC2. You can scale out your site by using this institution AMI to launch added instances Use
the following process to create your own AMI using the AWS Administration Console:
*Configure an EC2 example and its attached EBS volumes in the exact way you want them created in
the custom AMI.
1. Log out of your instance, but do not stop or terminate it.
2. Log in to the AWS Management Console, display the EC2 page for your region, then click
Instances.
3. Choose the instance from which you want to create a custom AMI.
4. Click Actions and click Create Image.
5. Type a name for Image Name that is easily identifiable to you and, optionally, input text for
Image Description.
6. Click Create Image.
Read the message box that appears. To view the AMI standing, go to the AMIs page. Here you can
see your AMI being created. It can take a though to create the AMI. Plan for at least 20 minutes, or
slower if you’ve connected a lot of additional applications or data.
Q171) What Are The Main Features Of Amazon Cloud Front?
Answer:Amazon Cloud Front is a web service that speeds up delivery of your static and dynamic web
content, such as .html, .css, .js, and image files, to your users.CloudFront delivers your content through
a universal network of data centers called edge locations
Q172) What Are The Features Of The Amazon Ec2 Service?
Answer:Amazon Elastic Calculate Cloud (Amazon EC2) is a web service that provides secure,
resizable compute capacity in the cloud. It is designed to make web-scale cloud calculating easier for
designers. Amazon EC2’s simple web serviceinterface allows you to obtain and configure capacity
with minimal friction.
Q173) Explain Storage For Amazon Ec2 Instance.?
Answer:An instance store is a provisional storing type located on disks that are physically attached to
a host machine. ... This article will present you to the AWS instance store storage type, compare it to
AWS Elastic Block Storage (AWS EBS), and show you how to backup data stored on instance stores
to AWS EBS
Amazon SQS is a message queue service used by scattered requests to exchange messages through a
polling model, and can be used to decouple sending and receiving components

Q174) When attached to an Amazon VPC which two components provide connectivity with
external networks?
Answer:
• Internet Gateway {IGW)
• Virtual Private Gateway (VGW)
Q175) Which of the following are characteristics of Amazon VPC subnets?
Answer:
• Each subnet maps to a single Availability Zone.
• By defaulting, all subnets can route between each other, whether they are private or public.
Q176) How can you send request to Amazon S3?
Answer:Every communication with Amazon S3 is either genuine or anonymous. Authentication is a
process of validating the individuality of the requester trying to access an Amazon Web Services
(AWS) product. Genuine requests must include a autograph value that authenticates the request
sender. The autograph value is, in part, created from the requester’s AWS access keys (access key
identification and secret access key).
Q177) What is the best approach to anchor information for conveying in the cloud ?
Answer:Backup Data Locally. A standout amongst the most vital interesting points while overseeing
information is to guarantee that you have reinforcements for your information,
• Avoid Storing Sensitive Information. ...
• Use Cloud Services that Encrypt Data. ...
• Encrypt Your Data. ...
• Install Anti-infection Software. ...
• Make Passwords Stronger. ...
• Test the Security Measures in Place.
Q178) What is AWS Certificate Manager ?
Answer:AWS Certificate Manager is an administration that lets you effortlessly arrangement, oversee,
and send open and private Secure Sockets Layer/Transport Layer Security (SSL/TLS) endorsements
for use with AWS administrations and your inward associated assets. SSL/TLS declarations are
utilized to anchor arrange interchanges and set up the character of sites over the Internet and
additionally assets on private systems. AWS Certificate Manager expels the tedious manual procedure
of obtaining, transferring, and reestablishing SSL/TLS endorsements.
Q179) What is the AWS Key Management Service
Answer:AWS Key Management Service (AWS KMS) is an overseen benefit that makes it simple for
you to make and control the encryption keys used to scramble your information. ... AWS KMS is
additionally coordinated with AWS CloudTrail to give encryption key use logs to help meet your
inspecting, administrative and consistence needs.
Q180) What is Amazon EMR ?

Answer:Amazon Elastic MapReduce (EMR) is one such administration that gives completely oversaw
facilitated Hadoop system over Amazon Elastic Compute Cloud (EC2).
Q181) What is Amazon Kinesis Firehose ?
Answer:Amazon Kinesis Data Firehose is the least demanding approach to dependably stack gushing
information into information stores and examination devices. ... It is a completely overseen benefit
that consequently scales to coordinate the throughput of your information and requires no continuous
organization
Q182) What Is Amazon CloudSearch and its highlights ?
Answer:Amazon CloudSearch is a versatile cloud-based hunt benefit that frames some portion of
Amazon Web Services (AWS). CloudSearch is normally used to incorporate tweaked seek abilities
into different applications. As indicated by Amazon, engineers can set a pursuit application up and
send it completely in under 60 minutes.
Q183) Is it feasible for an EC2 exemplary occurrence to wind up an individual from a virtual
private cloud?
Answer:Amazon Virtual Private Cloud (Amazon VPC) empowers you to characterize a virtual system
in your very own consistently disengaged zone inside the AWS cloud, known as a virtual private
cloud (VPC). You can dispatch your Amazon EC2 assets, for example, occasions, into the subnets of
your VPC. Your VPC nearly looks like a conventional system that you may work in your very own
server farm, with the advantages of utilizing adaptable foundation from AWS. You can design your
VPC; you can choose its IP address extend, make subnets, and arrange course tables, organize portals,
and security settings. You can interface occurrences in your VPC to the web or to your own server
farm
Q184) Mention crafted by an Amazon VPC switch.
Answer:VPCs and Subnets. A virtual private cloud (VPC) is a virtual system committed to your AWS
account. It is consistently segregated from other virtual systems in the AWS Cloud. You can dispatch
your AWS assets, for example, Amazon EC2 cases, into your VPC.
Q185) How would one be able to associate a VPC to corporate server farm?
Answer:AWS Direct Connect empowers you to safely associate your AWS condition to your
onpremises server farm or office area over a standard 1 gigabit or 10 gigabit Ethernet fiber-optic
association. AWS Direct Connect offers committed fast, low dormancy association, which sidesteps
web access suppliers in your system way. An AWS Direct Connect area gives access to Amazon Web
Services in the locale it is related with, and also access to different US areas. AWS Direct Connect
enables you to consistently parcel the fiber-optic associations into numerous intelligent associations
called Virtual Local Area Networks (VLAN). You can exploit these intelligent associations with
enhance security, separate traffic, and accomplish consistence necessities.
Q186) Is it conceivable to push off S3 with EC2 examples ?
Answer:Truly, it very well may be pushed off for examples with root approaches upheld by local
event stockpiling. By utilizing Amazon S3, engineers approach the comparative to a great degree
versatile, reliable, quick, low-valued information stockpiling substructure that Amazon uses to follow
its own overall system of sites. So as to perform frameworks in the Amazon EC2 air, engineers utilize
the instruments giving to stack their Amazon Machine Images (AMIs) into Amazon S3 and to

exchange them between Amazon S3 and Amazon EC2. Extra use case may be for sites facilitated on
EC2 to stack their stationary substance from S3.
Q187) What is the distinction between Amazon S3 and EBS ?
Answer:EBS is for mounting straightforwardly onto EC2 server examples. S3 is Object Oriented
Storage that isn’t continually waiting be gotten to (and is subsequently less expensive). There is then
much less expensive AWS Glacier which is for long haul stockpiling where you don’t generally hope
to need to get to it, however wouldn’t have any desire to lose it.
There are then two principle kinds of EBS – HDD (Hard Disk Drives, i.e. attractive turning circles),
which are genuinely ease back to access, and SSD, which are strong state drives which are excessively
quick to get to, yet increasingly costly.
• Finally, EBS can be purchased with or without Provisioned IOPS.
• Obviously these distinctions accompany related estimating contrasts, so it merits focusing on
the distinctions and utilize the least expensive that conveys the execution you require.
Q188) What do you comprehend by AWS?
Answer:This is one of the generally asked AWS engineer inquiries questions. This inquiry checks
your essential AWS learning so the appropriate response ought to be clear. Amazon Web Services
(AWS) is a cloud benefit stage which offers figuring power, investigation, content conveyance,
database stockpiling, sending and some different administrations to help you in your business
development. These administrations are profoundly versatile, solid, secure, and cheap distributed
computing administrations which are plot to cooperate and, applications in this manner made are
further developed and escalade.
Q189) Clarify the principle components of AWS?
Answer:The principle components of AWS are:
Highway 53: Route53 is an exceptionally versatile DNS web benefit.
Basic Storage Service (S3): S3 is most generally utilized AWS stockpiling web benefit.
Straightforward E-mail Service (SES): SES is a facilitated value-based email benefit and enables one
to smoothly send deliverable messages utilizing a RESTFUL API call or through an ordinary SMTP.
Personality and Access Management (IAM): IAM gives enhanced character and security the board for
AWS account.
Versatile Compute Cloud (EC2): EC2 is an AWS biological community focal piece. It is in charge of
giving on-request and adaptable processing assets with a “pay as you go” estimating model.
Flexible Block Store (EBS): EBS offers consistent capacity arrangement that can be found in
occurrences as a customary hard drive.
CloudWatch: CloudWatch enables the controller to viewpoint and accumulate key measurements and
furthermore set a progression of cautions to be advised if there is any inconvenience.
This is among habitually asked AWS engineer inquiries questions. Simply find the questioner psyche
and solution appropriately either with parts name or with the portrayal alongside.

Q190) I’m not catching your meaning by AMI? What does it incorporate?
Answer:You may run over at least one AMI related AWS engineer inquiries amid your AWS designer
meet. Along these lines, set yourself up with a decent learning of AMI.
AMI represents the term Amazon Machine Image. It’s an AWS format which gives the data (an
application server, and working framework, and applications) required to play out the dispatch of an
occasion. This AMI is the duplicate of the AMI that is running in the cloud as a virtual server. You
can dispatch occurrences from the same number of various AMIs as you require. AMI comprises of
the followings:
A pull volume format for a current example
Launch authorizations to figure out which AWS records will inspire the AMI so as to dispatch the
occasions
Mapping for square gadget to compute the aggregate volume that will be appended to the example at
the season of dispatch
Q191) Is vertically scale is conceivable on Amazon occurrence?
Answer:Indeed, vertically scale is conceivable on Amazon example.
This is one of the normal AWS engineer inquiries questions. In the event that the questioner is hoping
to find a definite solution from you, clarify the system for vertical scaling.
Q192) What is the association among AMI and Instance?
Answer:Various sorts of examples can be propelled from one AMI. The sort of an occasion for the
most part manages the equipment segments of the host PC that is utilized for the case. Each kind of
occurrence has unmistakable registering and memory adequacy.
When an example is propelled, it gives a role as host and the client cooperation with it is same
likewise with some other PC however we have a totally controlled access to our occurrences. AWS
engineer inquiries questions may contain at least one AMI based inquiries, so set yourself up for the
AMI theme exceptionally well.
Q193) What is the distinction between Amazon S3 and EC2?
Answer:The contrast between Amazon S3 and EC2 is given beneath:
Amazon S3
Amazon EC2
The significance of S3 is Simple Storage Service. The importance of EC2 is Elastic Compute Cloud.
It is only an information stockpiling administration which is utilized to store huge paired files. It is a
cloud web benefit which is utilized to have the application made.
It isn’t required to run a server. It is sufficient to run a server.

It has a REST interface and utilizations secure HMAC-SHA1 validation keys. It is much the same as a
tremendous PC machine which can deal with application like Python, PHP, Apache and some other
database.
When you are going for an AWS designer meet, set yourself up with the ideas of Amazon S3 and
EC2, and the distinction between them.
Q194) What number of capacity alternatives are there for EC2 Instance?
Answer:There are four stockpiling choices for Amazon EC2 Instance:
• Amazon EBS
• Amazon EC2 Instance Store
• Amazon S3
• Adding Storage
Amazon EC2 is the basic subject you may run over while experiencing AWS engineer inquiries
questions. Get a careful learning of the EC2 occurrence and all the capacity alternatives for the EC2
case.
Q195) What are the security best practices for Amazon Ec2 examples?
Answer:There are various accepted procedures for anchoring Amazon EC2 occurrences that are
pertinent whether occasions are running on-preface server farms or on virtual machines. How about
we view some broad prescribed procedures:
Minimum Access: Make beyond any doubt that your EC2 example has controlled access to the case
and in addition to the system. Offer access specialists just to the confided in substances.
Slightest Privilege: Follow the vital guideline of minimum benefit for cases and clients to play out the
capacities. Produce jobs with confined access for the occurrences.
Setup Management: Consider each EC2 occasion a design thing and use AWS arrangement the
executives administrations to have a pattern for the setup of the occurrences as these administrations
incorporate refreshed enemy of infection programming, security highlights and so forth.
Whatever be the activity job, you may go over security based AWS inquiries questions. Along these
lines, motivate arranged with this inquiry to break the AWS designer meet.
Q196) Clarify the highlights of Amazon EC2 administrations.
Answer:Amazon EC2 administrations have following highlights:
• Virtual Computing Environments
• Proffers Persistent capacity volumes
• Firewall approving you to indicate the convention
• Pre-designed layouts
• Static IP address for dynamic Cloud Computing
Q197) What is the system to send a demand to Amazon S3?
Answer: Reply: There are 2 different ways to send a demand to Amazon S3 –

• Using REST API
• Using AWS SDK Wrapper Libraries, these wrapper libraries wrap the REST APIs for
Amazon
Q198) What is the default number of basins made in AWS?
Answer:This is an extremely straightforward inquiry yet positions high among AWS engineer inquiries
questions. Answer this inquiry straightforwardly as the default number of pails made in each AWS
account is 100.
Q199) What is the motivation behind T2 examples?
Answer:T2 cases are intended for
Providing moderate gauge execution
Higher execution as required by outstanding task at hand
Q200) What is the utilization of the cradle in AWS?
Answer:This is among habitually asked AWS designer inquiries questions. Give the appropriate
response in straightforward terms, the cradle is primarily used to oversee stack with the
synchronization of different parts i.e. to make framework blame tolerant. Without support, segments
don’t utilize any reasonable technique to get and process demands. Be that as it may, the cushion
makes segments to work in a decent way and at a similar speed, hence results in quicker
administrations.
Q201) What happens when an Amazon EC2 occurrence is halted or ended?
Answer:At the season of ceasing an Amazon EC2 case, a shutdown is performed in a typical way.
From that point onward, the changes to the ceased state happen. Amid this, the majority of the
Amazon EBS volumes are stayed joined to the case and the case can be begun whenever. The
occurrence hours are not included when the occasion is the ceased state.
At the season of ending an Amazon EC2 case, a shutdown is performed in an ordinary way. Amid
this, the erasure of the majority of the Amazon EBS volumes is performed. To stay away from this,
the estimation of credit deleteOnTermination is set to false. On end, the occurrence additionally
experiences cancellation, so the case can’t be begun once more.
Q202) What are the mainstream DevOps devices?
Answer:In an AWS DevOps Engineer talk with, this is the most widely recognized AWS inquiries for
DevOps. To answer this inquiry, notice the well known DevOps apparatuses with the kind of
hardware –
• Jenkins – Continuous Integration Tool
• Git – Version Control System Tool
• Nagios – Continuous Monitoring Tool
• Selenium – Continuous Testing Tool
• Docker – Containerization Tool
• Puppet, Chef, Ansible – Deployment and Configuration Administration Tools.

Q203) What are IAM Roles and Policies, What is the difference between IAM Roles and
Policies.
Answer:Roles are for AWS services, Where we can assign permission of some AWS service to other
Service.
Example – Giving S3 permission to EC2 to access S3 Bucket Contents.
Policies are for users and groups, Where we can assign permission to user’s and groups.
Example – Giving permission to user to access the S3 Buckets.
Q204) What are the Defaults services we get when we create custom AWS VPC?
Answer:
• Route Table
• Network ACL
• Security Group
Q205) What is the Difference Between Public Subnet and Private Subnet ?
Answer:Public Subnet will have Internet Gateway Attached to its associated Route Table and Subnet,
Private Subnet will not have the Internet Gateway Attached to its associated Route Table and Subnet
Public Subnet will have internet access and Private subnet will not have the internet access directly.
Q206) How do you access the Ec2 which has private IP which is in private Subnet ?
Answer: We can access using VPN if the VPN is configured into that Particular VPC where Ec2 is
assigned to that VPC in the Subnet. We can access using other Ec2 which has the Public access.
Q207) We have a custom VPC Configured and MYSQL Database server which is in Private
Subnet and we need to update the MYSQL Database Server, What are the Option to do so.
Answer:By using NAT Gateway in the VPC or Launch a NAT Instance ( Ec2) Configure or Attach
the NAT Gateway in Public Subnet ( Which has Route Table attached to IGW) and attach it to the
Route Table which is Already attached to the Private Subnet.
Q208) What are the Difference Between Security Groups and Network ACL
Answer:
Security Groups Network ACL
Attached to Ec2 instance Attached to a subnet.
Stateful – Changes made in Stateless – Changes made incoming
rules is automatically in incoming rules is

not applied to the outgoing

applied to the outgoing rule rule
Blocking IP Address can’t be

IP Address can be Blocked done
Allow rules only, by default all Allow and Deny can be rules
are denied Used.
Q209) What are the Difference Between Route53 and ELB?
Answer:Amazon Route 53 will handle DNS servers. Route 53 give you web interface through which
the DNS can be managed using Route 53, it is possible to direct and failover traffic. This can be
achieved by using DNS Routing Policy.
One more routing policy is Failover Routing policy. we set up a health check to monitor your
application endpoints. If one of the endpoints is not available, Route 53 will automatically forward the
traffic to other endpoint.
Elastic Load Balancing
ELB automatically scales depends on the demand, so sizing of the load balancers to handle more
traffic effectively when it is not required.
Q210) What are the DB engines which can be used in AWS RDS?
Answer:
• MariaDB
• MYSQL DB
• MS SQL DB
• Postgre DB
• Oracle DB
Q211) What is Status Checks in AWS Ec2?
Answer: System Status Checks – System Status checks will look into problems with instance which
needs AWS help to resolve the issue. When we see system status check failure, you can wait for AWS
to resolve the issue, or do it by our self.
• Network connectivity
• System power
• Software issues Data Centre’s
• Hardware issues
• Instance Status Checks – Instance Status checks will look into issues which need our
involvement to fix the issue. if status check fails, we can reboot that particular instance.
• Failed system status checks
• Memory Full
• Corrupted file system
• Kernel issues
Q212) To establish a peering connections between two VPC’s What condition must be met?
Answer:
• CIDR Block should overlap
• CIDR Block should not overlap

• VPC should be in the same region
• VPC must belong to same account.
• CIDR block should not overlap between vpc setting up a peering connection . peering
connection is allowed within a region , across region, across different account.
Q213) Troubleshooting with EC2 Instances:
Answer: Instance States
• If the instance state is 0/2- there might be some hardware issue • If the instance state is 1⁄2-
there might be issue with OS.
Workaround-Need to restart the instance, if still that is not working logs will help to fix the
issue.
Q214) How EC2instances can be resized.
Answer: EC2 instances can be resizable(scale up or scale down) based on requirement
Q215) EBS: its block-level storage volume which we can use after mounting with EC2 instances.
Answer:For types please refer AWS Solution Architect book.
Q216) Difference between EBS,EFS and S3
Answer:
• We can access EBS only if its mounted with instance, at a time EBS can be mounted only
with one instance.
• EFS can be shared at a time with multiple instances
• S3 can be accessed without mounting with instances
Q217) Maximum number of bucket which can be crated in AWS.
Answer:100 buckets can be created by default in AWS account.To get more buckets additionally you
have to request Amazon for that.
Q218) Maximum number of EC2 which can be created in VPC.
Answer:Maximum 20 instances can be created in a VPC. we can create 20 reserve instances and
request for spot instance as per demand.
Q219) How EBS can be accessed?
Answer:EBS provides high performance block-level storage which can be attached with running EC2
instance. Storage can be formatted and mounted with EC2 instance, then it can be accessed.
Q220)Process to mount EBS to EC2 instance
Answer:
• Df –k
• mkfs.ext4 /dev/xvdf
• Fdisk –l
• Mkdir /my5gbdata

• Mount /dev/xvdf /my5gbdata
Q221) How to add volume permanently with instance.
Answer:With each restart volume will get unmounted from instance, to keep this attached need to
perform below step
Cd /etc/fstab
/dev/xvdf /data ext4 defaults 0
0 <edit the file system name accordingly>
Q222) What is the Difference between the Service Role and SAML Federated Role.
Answer: Service Role are meant for usage of AWS Services and based upon the policies attached to
it,it will have the scope to do its task. Example : In case of automation we can create a service role and
attached to it.
Federated Roles are meant for User Access and getting access to AWS as per designed role. Example
: We can have a federated role created for our office employee and corresponding to that a Group will
be created in the AD and user will be added to it.
Q223) How many Policies can be attached to a role.
Answer: 10 (Soft limit), We can have till 20.
Q224) What are the different ways to access AWS.
Answer:3 Different ways (CLI, Console, SDK)
Q225) How a Root AWS user is different from in IAM User.
Answer: Root User will have acces to entire AWS environment and it will not have any policy
attached to it. While IAM User will be able to do its task on the basis of policies attached to it.
Q226) What do you mean by Principal of least privilege in term of IAM.
Answer: Principal of least privilege means to provide the same or equivalent permission to the
user/role.
Q227)What is the meaning of non-explicit deny for an IAM User.
Answer: When an IAM user is created and it is not having any policy attached to it,in that case he will
not be able to access any of the AWS Service until a policy has been attached to it.
Q228) What is the precedence level between explicit allow and explicit deny.
Answer: Explicit deny will always override Explicit Allow.
Q229) What is the benefit of creating a group in IAM.

Answer:Creation of Group makes the user management process much simpler and user with the same
kind of permission can be added in a group and at last addition of a policy will be much simpler to the
group in comparison to doing the same thing manually.
Q230) What is the difference between the Administrative Access and Power User Access in term
of pre-build policy.
Answer: Administrative Access will have the Full access to AWS resources. While Power User
Access will have the Admin access except the user/group management permission.
Q231) What is the purpose of Identity Provider.
Answer: Identity Provider helps in building the trust between the AWS and the Corporate AD
environment while we create the Federated role.
Q232) What are the benefits of STS (Security Token Service).
Answer: It help in securing the AWS environment as we need not to embed or distributed the AWS
Security credentials in the application. As the credentials are temporary we need not to rotate them
and revoke them.
Q233) What is the benefit of creating the AWS Organization.
Answer: It helps in managing the IAM Policies, creating the AWS Accounts programmatically, helps
in managing the payment methods and consolidated billing.
Q234) What is the maximum file length in S3?
Answer: utf-8 1024 bytes
Q235) which activity cannot be done using autoscaling?
Answer:Maintain fixed running of ec2
Q236) How will you secure data at rest in EBS?
Answer: EBS data is always secure
Q237) What is the maximum size of S3 Bucket?
Answer: 5TB
Q238) Can objects in Amazon s3 be delivered through amazon cloud front?
Answer:Yes
Q239) which service is used to distribute content to end user service using global network of
edge location?
Answer: Virtual Private Cloud
Q240) What is ephemaral storage?
Answer: Temporary storage

Q241) What are shards in kinesis aws services?
Answer: Shards are used to store data in Kinesis.
Q242) Where can you find the ephemeral storage?
Answer: In Instance store service.
Q243) I have some private servers on my premises also i have distributed some of My workload
on the public cloud,what is the architecture called?
Answer:Virtual private cloud
Q244)Route 53 can be used to route users to infrastructure outside of aws.True/false?
Answer: False
Q245) Is simple workflow service one of the valid Simple Notification Service subscribers?
Answer: No
Q246) which cloud model do Developers and organizations all around the world leverage
extensively?
Answer: IAAS-Infrastructure as a service.
Q247) Can cloud front serve content from a non AWS origin server?
Answer: No
Q248) Is EFS a centralised storage service in AWS?
Answer: Yes
Q249) Which AWS service will you use to collect and process ecommerce data for near real time
analysis?
Answer: Both Dynamo DB & Redshift
Q250)An high demand of IOPS performance is expected around 15000.Which EBS volume type
would you recommend?
Answer: Provisioned IOPS.
