# AWS
AWS Zero-To-Hero

#### Day1: 
What is public cloud ?
What is private cloud?
why AWS is popular ?
Create an AWS account ?

#### Day2: IAM (Identity and Access Management)
In login time you see Login as a Root user and Login as a IAM User-> Root user give only some permissions to that IAM user some what new employee not able to delete created resources or not able to enter into some databases secret data Like this.

It is an AWS service is doing an Authentication( Check user Identity or User Profile) & Authorization( What access they have after authenticated OR after authenticated what resources the person accessed)  for you.
##### Users (Like Employees)
##### Policies (Permissions EC2 full access, S3 full access like this)
##### Groups (some of users)
##### Roles (From one service to anethor service If you want have an access then you gonna use called a Role)
Creating users and attaching some permissions means policies for each and every user is difficult, it requires manual work to attach policies so create the group of some permissions and add users to that group is simple.
creting users -> Add to group
Create Group -> Users add to that group

CMD   -----   AWS CLI -------AWS Account
Through AWS CLI connect to AWS Account through Access key and secret key region o/p format

After entering this use commands Search on google AWS Documentation for creating buckets, creating IAM user or anything you want to do.


#### EC2 (Elastic Compute Cloud)
