# interview-assignment

# TASK 1

kubernetes-challenge

# Kubernetes challenge

Deploy this application to [Minikube](https://github.com/kubernetes/minikube) and customise the environment variable to display your name.

```
$ curl $(minikube ip)
Hello kube!
```

## Instructions

- Fork this repo
- Build the Docker image
- Write yaml files for a deployment, service, ingress and configmap
- Deploy your application to Minikube
- You should be able to `curl` Minikube's ip and retrieve the string `Hello {yourname}!`
- Commit your files to Github

## Notes

There's no need to push the Docker image to a Docker registry. You should be able to build and use the image from within Minikube.

You can expose Minikube's Docker daemon with:

```shell
$ eval (minkube docker-env)
```

=======================================================================================================================================

# TASK 2
=======================================================================================================================================

Create High-availability autoscaling kubernetes cluster with terraform . on (AWS, GCP ) cloud.

-- custer should be in private VPC .
-- all nodes should be having private IP only no public Ip to nodes in cluster.

## Instructions
- Fork this repo
- create terrafrom script deploying stack.
- create makefile to deploy entire stack with teraform.
- deploy your simple hello world application on kubernetes cluster.


=======================================================================================================================================
