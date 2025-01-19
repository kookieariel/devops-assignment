# devops-assignment
Creating a users and adding roles as part of the Grafana Helm Chart installation process. 

The files I modified and added are: Values.yaml, /templates/grafana-users.yaml, /templates/deployment.yaml
* Values.yaml - contains only the values I would add in the file to create the ConfigMap and deploy it to the pod. 
* /templates/grafana-users.yaml - ConfigMap that reads the users list from Values.yaml file. 
* /templates/deployment.yaml- Mounthing the ConfigMap users data to /etc/grafana/provisioning in the pod. 
