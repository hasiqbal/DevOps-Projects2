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



