# Lab 1 - Introduction to AWS Identity and Access Management (IAM)

## Title
Introduction to AWS Identity and Access Management (IAM)


## Objective
The objective of this lab is to understand how AWS Identity and Access Management (IAM) controls authentication and authorization in AWS. The lab focuses on exploring IAM users and groups, analyzing attached policies, assigning users to appropriate groups based on organizational roles, and validating permissions by testing service access.


## Prerequisites
- Basic understanding of cloud computing concepts  
- AWS Academy Lab access  
- Web browser with internet connectivity  


## Tools Used
- AWS Management Console  
- AWS Identity and Access Management (IAM)  
- Amazon EC2  
- Amazon S3  


## Tasks Performed

### Task 1: Explore IAM Users and Groups
- Reviewed pre-created IAM users: user-1, user-2, user-3  
- Explored IAM groups: EC2-Admin, EC2-Support, S3-Support  
- Inspected managed and inline policies attached to groups  
**Screenshot:**  
<img width="1920" height="1080" alt="Screenshot (253)" src="https://github.com/user-attachments/assets/592b9ff6-2712-44cb-8bf9-7c6fcc5de27c" />
<img width="1920" height="1080" alt="Screenshot (254)" src="https://github.com/user-attachments/assets/214f2814-0990-423b-9d34-506e4b79f06f" />


### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  
<img width="1920" height="1080" alt="Screenshot (255)" src="https://github.com/user-attachments/assets/068b4ffa-45f4-4b8b-a670-b01391efa7fc" />
<img width="1920" height="1080" alt="Screenshot (256)" src="https://github.com/user-attachments/assets/918f3313-63df-4412-a005-ca0333e4838e" />
<img width="1920" height="1080" alt="Screenshot (257)" src="https://github.com/user-attachments/assets/ab77b1b1-1ee3-44f1-a950-4d53b4941fd8" />


### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**  
<img width="1920" height="1080" alt="Screenshot (258)" src="https://github.com/user-attachments/assets/b96fa749-1ad8-4c76-8496-8f6c607786d6" />
<img width="1920" height="1080" alt="Screenshot (259)" src="https://github.com/user-attachments/assets/ca8a037f-7b5e-4603-b56a-ba4709a59d9b" />
<img width="1920" height="1080" alt="Screenshot (260)" src="https://github.com/user-attachments/assets/c524f96a-deac-4251-a30d-8400c425df89" />
<img width="1920" height="1080" alt="Screenshot (261)" src="https://github.com/user-attachments/assets/a509fb03-8d6a-4ff1-8bef-0b2f452511c5" />



## Workflow
1. Accessed IAM console and reviewed users and groups.  
2. Inspected policy permissions attached to groups.  
3. Assigned users to groups based on their roles.  
4. Logged in as each IAM user using the sign-in URL.  
5. Validated permissions by accessing AWS services.  


## Learning Outcomes
- Understood the role of IAM in AWS security.  
- Learned how IAM users, groups, and policies interact.  
- Gained practical experience implementing role-based access control.  
- Verified permission enforcement through real-time service testing.  


## Conclusion
This lab provided hands-on experience with AWS IAM by demonstrating how organizations manage secure access to cloud resources. Assigning users to groups with predefined policies simplified permission management and ensured role-based access control across AWS services.


## Author
**Name:** Your Name and (Reg No)
**Course:** Introduction to Cloud Computing  

