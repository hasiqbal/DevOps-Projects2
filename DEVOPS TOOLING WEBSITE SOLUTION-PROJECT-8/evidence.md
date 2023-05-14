In this project you will implement a solution that consists of following components:

1. Infrastructure: AWS
2. Webserver Linux: Red Hat Enterprise Linux 8
3. Database Server: Ubuntu 20.04 + MySQL
4. Storage Server: Red Hat Enterprise Linux 8 + NFS Server
5. Programming Language: PHP
6. Code Repository: GitHub

On the diagram below you can see a common pattern where several stateless Web Servers share a common database and also access 
the same files using Network File Sytem (NFS) as a shared file storage. Even though the NFS server might be located on a completely 
separate hardware – for Web Servers it look like a local file system from where they can serve the same files.


![6000](https://user-images.githubusercontent.com/85270361/210138947-340454da-2ca8-4041-84e7-324d685612a4.PNG)




*Launched Webservers, NFS, and DB
![launched webservers, nfs and db](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/86ddc76f-8376-42f8-9a59-c92951e4db6e)

*Created and Attached 3 Volumes - Step 2
![created and attached 3 volumes - step2](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/a8413945-7df7-49c3-b52e-dbb6df65a071)

*SSH into NFS Server - Step 3 - and all other servers
![ssh in to nfs server step 3](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/6d1dbcc0-3760-43a2-8690-728737368a42)

*New Volumes Attached to NFS - Step 4
![new vols attached to nfs step4](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/fe29b335-1bd4-4026-bcb3-607736e95f39)

*Created Partitions - Step 5
![created partions step5](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/62460a2a-071b-46e6-9181-79dd1beb7052)

![step6](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/a4d6e490-7bd2-4f06-bb53-8adcf89dc76e)

*Created PVS
![created pvs step7](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/9495c6e2-80c6-46b4-9e55-86afb2e34c4e)

*Webdata Volume grouo
![step8 created webdata-vg](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/36d9793f-a81b-4b18-917a-9e80d3981499)

*Logical Volumes
![step 9 logical volumes](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/0a13acc5-81e1-48a3-a0bd-1923b727e15c)

*Mounted Volumes
![step10 mounted volumes](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/183dcdb7-1f0d-46da-bbdc-4d5ff0aa80ae)

*Setting up MYSQL
![step 11 mysql user](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/3719bcca-cc5c-4579-9c9b-f1f858a95293)

*NFS running
![step12 nfs running](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/0dde1c57-a1a0-40c8-9cfe-14d0a6938303)

*Exporting
![step13 export](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/ac037b51-2513-4169-8960-6bf310643a56)

*SG rules
![step14 sg rules](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/94bd89ae-8b86-4ffa-a0d0-64eea81d8db6)

*Login page
![final](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/656ae2d9-1832-4e2f-b0ba-567ce60d75d1)

*Web page
![final final](https://github.com/hasiqbal/DevOps-Projects2/assets/85685078/c08e71f6-f74f-494c-9584-c9dcba3e0093)

