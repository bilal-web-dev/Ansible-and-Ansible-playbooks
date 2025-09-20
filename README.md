# Ansible-and-Ansible-playbooks
Ansible Hands-on with Project

I have used Ansible (an open-source configuration management tool) to update the host servers using the push technique on AWS. The steps are as follows:

1. I created the Ansible master server on EC2 that will be responsible for updates and configuration of other host servers. 

<img width="1919" height="780" alt="image" src="https://github.com/user-attachments/assets/ccd9053a-1e0b-45ea-8605-3313808ffe62" />

# 2. I created 3 EC2 host servers, which will be updated using the Ansible master server. I used the same private key as the Master Server. 

<img width="1919" height="831" alt="image" src="https://github.com/user-attachments/assets/b790b393-b1e3-4d97-be30-633c4aae338a" />

# 3. I connected the Master server using Secure Shell of my PC and installed Ansible on it. 

<img width="1919" height="831" alt="image" src="https://github.com/user-attachments/assets/bb89f178-2f27-4aa5-a9ca-7bd57a31e485" />

# 4. After Ansible is installed, I have attached the Public IPs of host servers along with other required variables, including the authentication key, in the Ansible hosts file. 

<img width="1919" height="830" alt="image" src="https://github.com/user-attachments/assets/6c39d9f3-78c0-403a-9641-404573379daf" />

# 5. I tried to ping the servers to see if everything is working perfectly. Okay, success!..... After this, I checked the memory resources and ran the update command, and all of the host servers were updated. 

<img width="1919" height="835" alt="image" src="https://github.com/user-attachments/assets/6087fee6-72ab-4f27-bf97-314273411fae" />

<img width="1919" height="829" alt="image" src="https://github.com/user-attachments/assets/85743017-b50f-49c2-a878-105c285493e4" />
<img width="1919" height="597" alt="image" src="https://github.com/user-attachments/assets/977e8a41-cd2e-479c-b058-1ccfd804aa5a" />











   
