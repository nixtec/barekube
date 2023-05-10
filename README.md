# barekube
 Bare-metal On-premises Kubernetes for Linux Admins


**Optimistic Design Goals:**
* Maintain a single Base Linux Image on control plane
* No VM or Host OS to be managed per node: no pain of managing OS or Software stacks on Nodes
* Automatically grow your cloud with a SDS (Software Defined Storage). Zero configuration required.
* Automated provisioning of Nodes
  * Network booting: Centrally control boot process on nodes
  * Automated partitioning of nodes: No manual preparation per node required
  * Automated inclusion to SDS (Software Defined Storage): Automagically scale-up your cloud overnight
  * Automatically create a minimalistic configuration from Template for Nodes which will be used upon boot
  * Automatically join Node to the cloud: Automagically scale-up your cloud overnight
* No knowledge of Kubernetes is required: Linux admin required only
* Deploy services as if it was a single Linux machine
* Logically manage your cloud's Physical Resources (CPU/Memory/Storage) and services from control plane.
* No Dockerfile, no docker image required since you can manage most of the software stacks in the Base Linux image. Manage your Cloud Software stack like you would manage in a single Linux box.

