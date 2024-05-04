Kubernetes Networking
a)container to container in a pod
containers with in a same pod can communicate with each other using localhost, so here we can run the two containers in the same pod and they can communicate with each other using localhost

b) pod to pod communication
contianers in different pods can communicate with each other using the pod ip address, so here we can run the two containers in the different pods and they can communicate with each other using the cluster ip service

notes:
we can get the service host address:
process.env.NAME_OF_SERVICE_SERVICE_HOST
