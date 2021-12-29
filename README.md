# Kubernetes challenge

Deploy this application to any public cloud Kubernetes Service OR [Minikube](https://github.com/kubernetes/minikube) and customize the environment variable to display your name.

```
$ curl $(minikube ip)
Hello Foo!
```

## Instructions

- Fork this repo
- Build the Docker image
- Write yaml files for a deployment, service, ingress and configmap
- Deploy your application to any public cloud kubernetes service or Minikube
- You should be able to `curl` Server/Minikube's ip and retrieve the string `Hello {yourname}!`
- Commit your files to Github

## Notes

Use the container registry which your platform provides. You should be able to build and use the image from within Minikube if you use Minikube.

You can expose Minikube's Docker daemon with:

```shell
$ eval (minkube docker-env)
```
