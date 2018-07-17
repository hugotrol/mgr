# mgr
1) In group_vars edit ansible_remote_user parameter which is user that you use to connect to vm

2) make sure you use right inventory file:
  a) change user in inventory file, should be the same as ansible_remote_user

3) Token is pregenerated

4) on kubeslave main.yml role edit ip_address for master - I will fix that someday.

5) you can repeat playbook before the cluster is initialized on master KubeMasterNode

6) you can repeat playbook before slaves join to cluster

7) ansible need key for the machine - change the path in inventory



mm33ll
