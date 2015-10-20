## Kubernetes local machine docker based cluster

The obejctive of these scripts is to easily create/start/stop/remove a single node docker based Kubernetes cluster. Those commands were taken from Kubernetes [docs](http://kubernetes.io/v1.0/docs/getting-started-guides/docker.html).

## Interacting with the cluster

To interact with the cluster, you just need to download the kubectl binary for [linux](https://storage.googleapis.com/kubernetes-release/release/v0.18.2/bin/linux/amd64/kubectl) or [OS X](https://storage.googleapis.com/kubernetes-release/release/v0.18.2/bin/darwin/amd64/kubectl). Note that OS X users also need to set up port foward via ssh

```bash
boot2docker ssh -L8080:localhost:8080
```
