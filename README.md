# OpenEMR Kubernetes Files

I created Kubernetes yaml files for running OpenEMR in a single local Kubernetes node.  I used the latest Windows Fast Ring WSL2 and Docker Desktop Edge as of 2/9/2020.    

Download the four files: mysql-pv.yaml, mysql-deployment.yaml, openemr-pv.yaml, openemr-deployment.yaml.  

Use kubectl apply -f <yaml file name> to create volumes, services and deployments.  Process them in the order listed above.
