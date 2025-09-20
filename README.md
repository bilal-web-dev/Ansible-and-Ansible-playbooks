# Ansible-and-Ansible-playbooks


## Ansible Hands-on with Project

## I have used Ansible (an open-source configuration management tool) to update the host servers using the push technique on AWS. The steps are as follows:

## 1. I created the Ansible master server on EC2 that will be responsible for updates and configuration of other host servers. 

<img width="1919" height="780" alt="image" src="https://github.com/user-attachments/assets/ccd9053a-1e0b-45ea-8605-3313808ffe62" />

## 2. I created 3 EC2 host servers, which will be updated using the Ansible master server. I used the same private key as the Master Server. 

<img width="1919" height="831" alt="image" src="https://github.com/user-attachments/assets/b790b393-b1e3-4d97-be30-633c4aae338a" />

## 3. I connected the Master server using Secure Shell on my PC and installed Ansible on it. 

<img width="1919" height="831" alt="image" src="https://github.com/user-attachments/assets/bb89f178-2f27-4aa5-a9ca-7bd57a31e485" />

## 4. After Ansible is installed, I have attached the Public IPs of host servers along with other required variables, including the authentication key, in the Ansible hosts file. 

<img width="1919" height="830" alt="image" src="https://github.com/user-attachments/assets/6c39d9f3-78c0-403a-9641-404573379daf" />

## 5. I tried to ping the servers to see if everything is working perfectly. Okay, success!..... After this, I checked the memory resources and updated the host servers using the Ansible master server. 

<img width="1919" height="835" alt="image" src="https://github.com/user-attachments/assets/6087fee6-72ab-4f27-bf97-314273411fae" />

<img width="1919" height="829" alt="image" src="https://github.com/user-attachments/assets/85743017-b50f-49c2-a878-105c285493e4" />
<img width="1919" height="597" alt="image" src="https://github.com/user-attachments/assets/977e8a41-cd2e-479c-b058-1ccfd804aa5a" />



# Next step is to play with Ansible playbooks and YML for automation:

## Created and run a basic playbook that shows the date and uptime of host servers.

<img width="1919" height="837" alt="image" src="https://github.com/user-attachments/assets/e0c6dda5-94dc-4c85-8b34-ebd66e5e85f8" />
<img width="1919" height="758" alt="image" src="https://github.com/user-attachments/assets/733a2bb2-0e22-4d2c-9c76-4d21cfa734e8" />




## Now I will set up a separate production server, install the nginx web server, and deploy the static web page on it all using Ansible playbooks. Let's gp!


## Edited the Ansible hosts file. Now, we have one production server and separate servers.

<img width="1919" height="833" alt="image" src="https://github.com/user-attachments/assets/5d858b22-dd7b-4576-bfff-f65676c7dc93" />

## Created an HTML webpage to deploy it on the production server. 

<img width="1919" height="834" alt="image" src="https://github.com/user-attachments/assets/6f332a5d-d66a-4e27-bbcb-1a8eee7ef045" />

## Written an Ansible playbook yml file that will install, start, enable, and deploy the web page on the NGINX web server all by itself. 

<img width="1919" height="833" alt="image" src="https://github.com/user-attachments/assets/bbe1e529-c6bf-441d-a949-5f3884ad800b" />

##Time to run:

<img width="1919" height="719" alt="image" src="https://github.com/user-attachments/assets/c3ae02fe-f98f-4990-8358-ff4c1bce0906" />

## Hitting the public IP and we are LIVE!















   
