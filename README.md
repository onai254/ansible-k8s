# ansible-linode
Provisioning a linode Virtual machies and installing the lettest version of kubernetes, Helm and Argocd using ansible

Creating the tree directory for the project


mkdir group_vars

mkdir -p roles/{base,master,worker}/{handlers,task,templates}