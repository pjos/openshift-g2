# openshift-g2

### Wiki:https://github.com/pjos/openshift-g2/wiki

### The base is a CentOS 7 minimal installation (this step has already been ran on your laptop) 
```shell:
sudo yum -y install git
git clone https://github.com/pjos/openshift-g2.git
sudo openshift-g2/bin/bootstrap-oc-env
```

### Start local OpenShift cluster

```shell:
sudo oc cluster up
...
   You are logged in as:
       User:     developer
       Password: developer

   To login as administrator:
       oc login -u system:admin
...
sudo iptables --flush
```
