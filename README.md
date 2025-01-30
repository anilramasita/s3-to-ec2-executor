# s3-to-ec2-executor

# STEP BY STEP PROCEDURE

1. Run an ec2 instance from aws management console
2. Create a unique s3 bucket, upload ay files that you need to execute
3. Create an IAM role and change the security permissions for the instance you have created to that IAM role
4. Open unix/linux terminal and copy the ssh client path from the ec2 instance
5. Once you have connected, copy this to your command prompt "aws s3 cp s3://your-bucket-name/your-file-name /your-pwd/"
6. This will make a copy of file from s3 bucket to your working directory
7. Once finished, execute the file, ex: If it is python file then "python file-name.py"


![Image](https://github.com/user-attachments/assets/55f6150d-230a-48d2-9b99-0042251aa70f)
