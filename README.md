# SecondSemester_Cloud_Project
This repository is a Project examination assigned to me   ![logo-OYJ34ERC](https://github.com/user-attachments/assets/47476670-8680-4ca3-bf7b-dfb9331dcb38)

These are the steps and documentations of how I provisioned the server:
*I chose AWS as my cloud provider*
1. Launching and Configuring a New Instance: I launched a new instance, using Ubuntu as my as the operating system. I configured the CPU,memory and network settings based on the performance needs. I generated a new ssh key for my instance using AWS and saved the key in pem form as this key would be used to securely connect to my server.
2. Setting Up Security Groups: I defined the inbound  traffic to allow HTTP traffic (port 80) and I also defined HTTPS and TCP traffic.
3. Connecting to my server: Using my local terminal(bash) I connected to my server using the command: ssh -i ~/.ssh/sshKey.pem ubuntu@35.179.147.230.
4. Updating and Securing my Server: Once connected, I updated the package lists and upgraded installed packages. *sudo apt update && sudo apt upgrade -y*
