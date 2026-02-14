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

<img width="1919" height="907" alt="image" src="https://github.com/user-attachments/assets/5c0e759f-0105-46b0-af40-76c10ee28531" />

### Task 2: Add Users to Groups
- Added user-1 to the S3-Support group  
- Added user-2 to the EC2-Support group  
- Added user-3 to the EC2-Admin group  
**Screenshot:**  

<img width="1912" height="913" alt="Screenshot 2026-02-07 103950" src="https://github.com/user-attachments/assets/1c994aac-5764-44ec-b8f1-3afb6a954471" />

<img width="1913" height="919" alt="Screenshot 2026-02-07 104117" src="https://github.com/user-attachments/assets/4b48e60e-0638-4ee0-b694-5e7b4c3cdfb0" />

<img width="1919" height="972" alt="Screenshot 2026-02-07 104508" src="https://github.com/user-attachments/assets/2b48e963-6b59-4079-b4f2-bca4eac679fb" />

### Task 3: Test IAM User Permissions
- Logged in using IAM sign-in URL  
- Verified S3 access for user-1  
- Verified EC2 read-only access for user-2  
- Verified EC2 administrative access for user-3  
**Screenshot:**

<img width="1911" height="974" alt="Screenshot 2026-02-07 111247" src="https://github.com/user-attachments/assets/a4595929-4b3e-492e-b8a8-cd848fa9eb61" />

<img width="1919" height="978" alt="Screenshot 2026-02-07 110937" src="https://github.com/user-attachments/assets/a59f58e7-af0c-4ab9-91e1-564b0fbdf874" />

<img width="1919" height="970" alt="Screenshot 2026-02-07 111938" src="https://github.com/user-attachments/assets/454ff101-904f-4276-9656-6a3fabb56678" />

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
**Name:** PRADEEP N

**Reg No:** 212223060201

**Course:** Introduction to Cloud Computing  

