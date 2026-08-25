# CLOUD-STORAGE-CREATION-S3-AND-LAUNCHING-AN-EC2-INSTANCE-IN-AWS-
## Aim

To create an Amazon S3 bucket for cloud storage and launch a virtual machine using Amazon EC2 in the AWS Management Console.
Objectives

After completing this experiment, students will be able to:
•	Understand AWS Cloud Storage (Amazon S3). 
•	Create and manage S3 buckets. 
•	Upload and organize files in cloud storage. 
•	Launch an EC2 virtual server. 
•	Connect to an EC2 instance. 
•	Understand cloud computing infrastructure services. 

Software Requirements
•	Laptop/Desktop 
•	Internet Connection 
•	AWS Academy Learner Account / AWS Free Tier Account 
•	Modern Web Browser (Chrome/Edge) 

Theory
Amazon S3 (Simple Storage Service)
Amazon S3 is an object storage service provided by AWS that stores unlimited amounts of data with high durability and availability.
Features
•	Unlimited Storage 
•	99.999999999% (11 9's) durability 
•	High Availability 
•	Secure Storage 
•	Versioning 
•	Lifecycle Management 
•	Encryption
 Part A – Creating an Amazon S3 Bucket

Step 1

Open the AWS console.
URL: https://aws.amazon.com/console/

Step 2

Log in using the following method:

•	Click Sign in using root user email. 

•	Enter the registered email address. 

•	Enter the AWS password. 

•	Complete the verification process. 

## Output:

<img width="1482" height="672" alt="Screenshot 2026-08-25 084736" src="https://github.com/user-attachments/assets/cd33a119-541d-4472-abf1-41358396a5d3" />

Step 3

Type S3 in the search box.

## Output:

<img width="1502" height="712" alt="Screenshot 2026-08-25 084757" src="https://github.com/user-attachments/assets/4a6b4e36-edb8-4215-a1dd-6d5e933e57a9" />

Step 4
Click Amazon S3.

Step 5
Click Create bucket.
## Output:

Step 6

Enter the following details.

Parameter	Value

Bucket type	General purpose

Bucket name	student-cloud-storage-001

AWS Region	Asia Pacific (Mumbai)

Step 7
Leave the remaining settings unchanged.

Step 8
Click Create bucket.

Step 9
Click Upload.

Step 10

Upload the following files:
•	PDF file 
•	Word document 
•	Image file 

Example

student-cloud-storage-001

├── Cloud.pdf

├── Assignment.docx

├── Image.jpg

└── Notes.pdf
<img width="1493" height="646" alt="Screenshot 2026-08-25 084707" src="https://github.com/user-attachments/assets/d28b627a-1403-4053-be7c-26371ef97dd1" />

Part B – Launching an Amazon EC2 Instance

Step 1

Type EC2 in the AWS search bar.

<img width="1347" height="695" alt="Screenshot 2026-08-25 084831" src="https://github.com/user-attachments/assets/41157201-2049-482c-873e-dd440de8ac45" />

Step 2
Open the EC2 Dashboard.

Step 3
Click Launch instance.

Step 4
Enter the instance name.
CloudLabVM

Step 5
Select the operating system.
•	Amazon Linux 2023 
•	Ubuntu Server 

Step 6
Select the instance type.
t3.micro

Step 7
Create a key pair.
Parameter	Value
Key pair name	CloudLabKey
Key pair type	RSA

Step 8
Download the CloudLabKey.pem file.

Step 9
Configure the network settings.
✅ Allow SSH traffic (Port 22)
✅ Allow HTTP traffic (Port 80)
✅ Allow HTTPS traffic (Port 443)

Step 10
Set the storage size.
8 GiB

Step 11
Click Launch instance.

Step 12
Wait until the status changes.
Pending
   ↓
Running

<img width="1490" height="688" alt="Screenshot 2026-08-25 085618" src="https://github.com/user-attachments/assets/07dcb3f2-9dff-4435-86c6-7ac936a53621" />

Connecting to the EC2 Instance
Step 1
Open EC2.

Step 2
Select the instance.

Step 3
Click Connect.

Step 4
Select EC2 Instance Connect.

Step 5
Click Connect.

Step 6
Execute the following command:
echo "Hello AWS"

## Output

<img width="1535" height="618" alt="Screenshot 2026-08-25 085813" src="https://github.com/user-attachments/assets/7b00ae71-70a8-455d-9e91-e6b97d030bd5" />

Hello AWS

Stopping the EC2 Instance
Step 1
Open EC2.

Step 2
Select Instances.

Step 3
Select the running instance.

Step 4
Click Instance state.

Step 5
Click Stop instance.

Status
Running
   ↓
Stopping
   ↓
Stopped

Logging Out of AWS
1.	Click the profile icon in the upper-right corner. 
2.	Select Sign out. 

Result
The Amazon S3 bucket was created successfully, files were uploaded, an EC2 instance was launched, and the virtual machine was connected successfully.

