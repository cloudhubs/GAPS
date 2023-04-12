# Train Ticket Microservice Project

This is a slightly modified version of the train-ticket microservice system for use with testing our Grafana plugin. 

To deploy train ticket with jaeger, first set up a kubernetes cluster.

Next, navigate to `deployment/kubernetes-manifests/k8s-with-jaeger`

Finally, run 

`kubectl apply -f ts-deployment-part1.yml`

`kubectl apply -f ts-deployment-part2.yml`

`kubectl apply -f ts-deployment-part3.yml`

Train Ticket will be running on port 32677 and the Jaeger page will be on port 32688.

The user account on Train Ticket is fsde_microservice with password 111111 and the admin account is admin with password 222222
