# barekube
 Bare-metal On-premises Kubernetes for Linux Admins

**Design Goals:**
* Maintain a single Base Linux Image
* Automated provisioning of Nodes
  * Automated partitioning
  * Automated inclusion to SDS (Software Defined Storage)
* No OS to be installed in nodes other than Master (Control Plane) node
* No knowledge of Kubernetes is required
* Deploy services as if it was a single Linux machine
