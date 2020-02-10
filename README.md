# OpenEMR Kubernetes Files

I created Kubernetes yaml files for running OpenEMR in a local single node Kubernetes cluster.  I used the latest Windows Fast Ring WSL2 and Docker Desktop Edge as of 2/9/2020.  I've also tested on a Mac using Docker Desktop.  

Download the four files: mysql-pv.yaml, mysql-deployment.yaml, openemr-pv.yaml, openemr-deployment.yaml. Edit the persistent volume paths in mysql-pv.yaml and openemr-pv.yaml as appropriate.

Use kubectl apply -f (yaml file name) to create volumes, services and deployments.  Process them in the order listed above.
