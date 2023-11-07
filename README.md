# interview-web-app
Interview web app

This cluster is designed to be launched with [kind](https://kind.sigs.k8s.io/docs/user/quick-start)
=============================================

Kustomize Option
===============

Dependencies:
* kind
* kubectl
* terminal

Visibility into the cluster can be done with kubectl only,
but a tool like [k9s](https://k9scli.io/topics/install/) is very nice to have

```
cd /tmp/; git clone https://github.com/jdautomate/interview-web-app.git
cd interview-web-app/kustomize
kind create cluster
kubectl apply -k .
```

Helm Option
===========

```
cd /tmp/; git clone https://github.com/jdautomate/interview-web-app.git
cd interview-web-app
kind create cluster
helm install web-app helm/
```