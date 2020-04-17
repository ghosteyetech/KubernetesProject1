# KubernetesProject1
Initial learning project about Kubernetes

## GCloud Commands for Postgres
```
$ gcloud init
$ gcloud auth list
$ gcloud projects list 
$ gcloud sql instances patch <DB Instance name> --require-ssl 
```

## Minikube
Check that it is properly installed, by running the minikube version command:
```
$ minikube version
```

Start the cluster, by running the minikube start command:
```
$ minikube start
```

## kubectl
After starting Minkube, To check if kubectl is installed you can run the kubectl version command:
```
$ kubectl version
```

## Cluster details
Let’s view the cluster details. We’ll do that by running kubectl cluster-info:
```
$ kubectl cluster-info
```

To view the nodes in the cluster, run the kubectl get nodes command:
```
$ kubectl get nodes
```

This command shows all nodes that can be used to host our applications. Now we have only one node, and we can see that its status is ready (it is ready to accept applications for deployment).

## Using kubectl to Create a Deployment




