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

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/cdb6cc29-464b-4e61-b116-e577f26f14fe" />

Step 3

Type S3 in the search box.

## Output:
<img width="1664" height="837" alt="Screenshot 2026-08-21 215535" src="https://github.com/user-attachments/assets/b69e5840-3793-4929-aca3-737ffece53d9" />

Step 4
Click Amazon S3.

Step 5
Click Create bucket.
## Output:
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/de689f8c-a815-4b38-8127-75ebfed9a4bc" />

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
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/25df8b2c-80ca-473c-be6a-31315b553dd5" />

Part B – Launching an Amazon EC2 Instance

Step 1

Type EC2 in the AWS search bar.
<img width="1656" height="834" alt="Screenshot 2026-08-21 220332" src="https://github.com/user-attachments/assets/179b9c5f-e9a7-4241-a804-95e4bbf9c9d7" />

Step 2
Open the EC2 Dashboard.

Step 3
Click Launch instance.

Step 4
Enter the instance name.
CloudLabVM
<img width="1672" height="941" alt="2" src="https://github.com/user-attachments/assets/ea487fe4-ee94-4591-9b92-47c04d01263a" />

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

Output

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
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/519ae9b3-27c9-4ca2-b06b-74e440e23b3d" />
Logging Out of AWS
1.	Click the profile icon in the upper-right corner. 
2.	Select Sign out. 

Result
The Amazon S3 bucket was created successfully, files were uploaded, an EC2 instance was launched, and the virtual machine was connected successfully.

