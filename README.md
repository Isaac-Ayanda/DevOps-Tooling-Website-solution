# DevOps-Tooling-Website-solution

I setup a Three-Tier architecture using AWS infrastructure and deployed a DevOps tooling website solution.
- The architectire comprises of a client, 2 linux Redhat webserver to serve the tooling app solution  to users, 1 linux Redhat NFS server as the storage server and an Ubuntu linux Database server as a shared file storage.
- I attached three volume disks to the NFS server and worked with some storage and disk management utlities that ensures that the disks used to store files on the Linux server are adequately partitioned and managed.
- I connected the webservers to the  nfs server and the database server so that all of the servers communicate with each other in replicating files accross the network, (so that if one of the webservers is offline the other servers will continue to serve content to clients) after which I deployed a DevOps tooling website solution.