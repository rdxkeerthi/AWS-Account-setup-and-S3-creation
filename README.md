# AWS-Account-setup-and-S3-creation
## Introduction
In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

## Objectives
- Create a Bucket in Amazon S3.
- Add Objects (files and folders) to the bucket.
- Access, move, download, and delete the objects.
- Delete the Bucket.
### Illustration
- **Step 1:** Choose S3 Service
Choose the S3 service from the list of services provided by AWS.

![image](https://github.com/user-attachments/assets/9c46a163-7852-40cc-ab3c-d7e057233c22)


- **Step 2:** Create a Unique Bucket
After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.

![image](https://github.com/user-attachments/assets/95f55118-e073-4584-b99b-ed8f87727c53)
![image](https://github.com/user-attachments/assets/c802718b-16af-4afd-a79e-54abbf0eea50)
![image](https://github.com/user-attachments/assets/0b880323-cb8a-4a11-a00c-2767ef62813f)
![image](https://github.com/user-attachments/assets/b3766475-7c58-4100-bfaf-69a504eb7f73)
![image](https://github.com/user-attachments/assets/5e27a46d-3ac9-4684-9d3b-7a71228f235e)
![image](https://github.com/user-attachments/assets/acc1ba8e-622f-4f35-ba95-eff541dfc101)



For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

- **Step 3:** Upload Files to the Bucket
Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

![image](https://github.com/user-attachments/assets/2a6300dc-4ee3-4e08-aafd-b710e20df281)
![image](https://github.com/user-attachments/assets/5fddfaaf-4464-4aaa-8fe2-ccad5c2dc802)


You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., https://s3-ap-southeast-2.amazonaws.com/...) to share it.

![image](https://github.com/user-attachments/assets/04fdd9af-c702-4c87-a22a-6c1175b89ea5)
![image](https://github.com/user-attachments/assets/41b17168-9db0-47a8-a12e-1c03b24d99a0)


- **Step 4:** Upload a Folder
You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.

![image](https://github.com/user-attachments/assets/a74a6fb1-a75b-4fff-84a3-06eb36f26f87)


- **Step 5:** Delete the Bucket
To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.

![image](https://github.com/user-attachments/assets/eb4d242c-fbde-4b14-9fb4-2cf6189f0e51)


### Result
Successfully created, managed, and deleted an S3 bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon S3.
