# AWS IAM User, Group & Policy Project

## Objective
To create IAM users, organize them into groups, and assign permissions using policies.

## Services Used
- AWS IAM(Identity & Access Management)

## Steps Performed
### 1. Created IAM Users
- Username: Nanditha
- Enabled AWS Management Console access
- Set Password and login details

## 2. Created IAM Group 
- Group name: Admin

## 3. Attached Policy to Group 
- Attached AWS managed policy:
   - AdministratorAccess

## 4. Added User to Group 
- Added "Nanditha" to AdministratorAccess

## 5. Tested Access

#####  Login as Nanditha
- Able to view AWS Services(EC2, S3)
- Unable to create or delete resources

## Issues Faced
### Issue:
- Access denied while trying to create EC2 instance

### Fix:
- Verified that AdministratorAccess policy was applied 

#### Outcome
   - Successfully implemented IAM access control for one user
   - Understood how group-based permission work
   - Learned how to test and verify access limitations


#### Screenshots
   - IAM User Creation
     <img width="1440" height="813" alt="IAM User" src="https://github.com/user-attachments/assets/679525e5-fd30-44be-b43d-7bbf02727243" />

   - IAM Group Creation
     <img width="1432" height="812" alt="IAM Group" src="https://github.com/user-attachments/assets/dd73bc5f-1ff8-4226-b586-3fc58aa814d5" />

   - Policy Attachment
     <img width="1436" height="814" alt="Policy" src="https://github.com/user-attachments/assets/ce3722c6-622e-43eb-a305-822d19a73455" />

   - Access Denied Error
     <img width="681" height="149" alt="Denied" src="https://github.com/user-attachments/assets/7e358661-ece4-45fc-9feb-ed10c39e4a2b" />

     

     
      





    

