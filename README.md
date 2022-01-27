**DevOps Engineer Assignment**
 
Here is our small Infrastructure/SRE assignment:
- [ ] We want to deploy a highly-available Elasticsearch (ES) cluster.
- [ ] It should be done using Docker and Kubernetes.
- [ ] The cluster should be on multiple hosts/worker nodes, rather than just multiple pods/containers. 
- [ ] The Elasticsearch roles assigned to the each cluster instance should be the same
- [ ] Can be deployed on cloud cluster or local machine

The solution should be delivered with all the code/configuration required to deploy the ES service, including Kubernetes manifests, scripts and configuration files. A nice README file would help a lot.

Below you will find a few things that we will take into account for evaluation. You don’t have to include these in your solution, but please consider how to tackle them as if it is deployed in production.

- Why deploy the cluster in a specific way, what is your rationale? Be prepared to justify and explain deployment configuration options.
- Which metrics to look out for and why?
- What would the deploy, debug, backup, update/roll-back, maintenance processes be?

In the next interview, it is required to have the cluster up and running. You will be asked to present your approach and provide the rationale for its implementation decisions.


ToDo:
- [ ] Deployment EKS cluster in AWS
- [ ] Prepere for deployment ELK stack on EKS
- [ ] Deployment ELK
- [ ] Deployment of Prometheus