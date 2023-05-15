
## AWS-DevOpsDailySheet

[DevOpsDailySheet](https://linktodocumentationDevOpsDailySheet)

⁕ On daily sheet I’ve to put daily note on project basis what I’ve learned and what issue I faced.

## Create an Account of AWS (Amazon Web Services)

Insert a link https://aws.amazon.com/ 


## Instance Creation## Cration Of an EC2(Elastic Compute Cloud) Instance

First of all what is an Instance and why we need it ?

An instance is a virtual machine that can be created on demand(in cloud) to run a specific application in the cloud. We need instances because they allow us to quickly and easily provision the computing resources needed to run applications without having to purchase or manage physical hardware, it allowing us to scale resources up or down(as per traffic flow) as needed to meet changes in demand, pay only for what they use.

1. On the home page of the AWS console we search for EC2 and then we click on it and then we go to the create page and there we see launch intance on the top right corner we just click on it we see a new page comes up on that page first we need to give a name to our instance according to our uses of it. Then we need to select our AMI(AmazonMachineImage) It is a pre-configured virtual machine image.

2. After selecting AMI we move to Instance type here we need to select hardware like RAM, ROM etc.

3. After that we select we need click on to create a key pair by simply giving a name to that Like Godrej locker and its key to log into it. It always in .pem format so create and download the key.

4. After that we go down below and select security group we can choose existing one cause when we create an AWS account it came by default. 
 Then we can simply hit the launch Instance to create a EC2 Instance. 

## How to connect a Instance 
For connect Instance we need a application called PuTTy and PuTTygen
by the help of two application we can log in to our Instance.