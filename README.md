# cloud-01
Lanching an Amazon EC2 instance on Linux
## Project Aims
-Creating an EC2 instance

-Configuring a security group group for SSH access

-Connecting to the instance through SSH

-Terminating operations
## Diagram
![cloud-01](https://github.com/user-attachments/assets/fac5c788-7500-45c4-9620-bd5ed2cf64a7)
## Steps
1. Navigate to the bar, type "EC2"
   ![Step-1](https://github.com/user-attachments/assets/04d8c0b4-5c0e-48a5-ae5e-d016a3c48fa5)

2. Chose an Amazon Machine Image(AMI) and select Ubuntu
   ![Step-2](https://github.com/user-attachments/assets/7f75a87c-3307-4168-a196-060bf74c33e1)

3. Selected the t3.micro instance type
   ![Step-3](https://github.com/user-attachments/assets/91221b0f-4d02-40b2-90b8-f28ac2a91eae)

4. Generated a key-pair that will be used to connect to the EC2 instance through SSH
   ![Step-4](https://github.com/user-attachments/assets/d9bc2ec3-f3d6-425d-87f4-ede3d21ac60b)

5. Enabled SSH traffic in the network settings
   ![Step-5](https://github.com/user-attachments/assets/34ccaaf3-1560-448c-a0fc-bb3fe12a683b)

6. Configured storage
   ![Step-6](https://github.com/user-attachments/assets/7cc97e0e-1d5b-4633-9387-7aa6d192b6cc)

7. Launched the instance
   ![Step-7](https://github.com/user-attachments/assets/a0290d6c-8640-4625-895f-ff9ce84faeac)

8. Navigated to security
   ![Step-8](https://github.com/user-attachments/assets/ae23b707-c3ab-45ad-b2e0-2b4658a9ae7e)

9. Added rules to connect the Linux instance via SSH to my IP address. To enhance security
    ![Step-9](https://github.com/user-attachments/assets/2f5c2d21-327a-4470-a37a-056774ed50fd)

11. Used the SSH command and the path to the private key, imstance username to connect my instance using SSH
    ![Step-11](https://github.com/user-attachments/assets/df2d7a6b-7e29-440c-ad1a-d56da1bcd158)

12. Successfully terminated the EC2 instance
    ![Step-12](https://github.com/user-attachments/assets/ed4a7b10-abe3-41b6-9cb5-d367068e8f58)


    






