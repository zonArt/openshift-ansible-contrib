# Reference Architecture for OpenShift
This repository contains a series of directories containing code used to deploy an OpenShift environment on different cloud providers. The code in this repository supplements the reference architecture guides for OpenShift 3.3. Different guides and documentation exists depending on the different providers. Regardless of the provider, the envionment will deploy 3 Masters, 2 infrastructure nodes and 2 applcation nodes. The code also deploys a Docker registry and scales the router to the number of Infrastruture nodes.

For documentation, please see the follwing links

AWS https://access.redhat.com/articles/2623521

GCP https://access.redhat.com/articles/2751521

VMWare https://access.redhat.com/articles/2745171
