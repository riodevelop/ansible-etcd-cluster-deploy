# ansible-etcd-cluster-deploy
Simple playbook for deploying etcd cluster

## Deploying process
1. Fill inventory example with your hosts for etcd, lan interface for communicating and preffer etcd version
2. Run playbook:
    ansible-playbook -i inventory.ini -kK install.yml

Tested on ansible 2.18.1 and Oracle Linux 9.5