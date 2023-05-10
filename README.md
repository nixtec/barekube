# barekube
 Bare-metal On-premises Kubernetes for Linux Admins

**Optimistic Design Goals:**
* Maintain a single Base Linux Image on control plane
* No VM or Host OS to be managed per node: no pain of managing OS or Software stacks on Nodes
* Automated provisioning of Nodes
  * Network booting: Centrally control boot process on nodes
  * Automated partitioning of nodes: No manual preparation per node required
  * Automated inclusion to SDS (Software Defined Storage): Automagically scale-up your cloud overnight
  * Automatically create a minimalistic configuration from Template for Nodes which will be executed  upon boot
  * Automatically join to the cloud: Automagically scale-up your cloud overnight
* No knowledge of Kubernetes is required: Linux admin required only
* Deploy services as if it was a single Linux machine
* Logically manage your cloud's Physical Resources (CPU/Memory/Storage) and services from control plane.


