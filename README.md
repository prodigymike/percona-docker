# percona-docker

Collection of Dockerfiles for Percona sofware.
See individual directories for more details.

**MY EDITS**



I've updated pxc-57 to be more Rancher & Kubernetes cluster friendly. It'll now work with Services to gather Container IPs that belong to it.
Helping the bootstrap process.

Beware, there are still issues with sync of server starting up correctly and the master assuming itself appropriately.

I am not a Kubernetes nor Rancher expert. Enjoy.