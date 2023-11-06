# interview-web-app
Interview web app

This cluster is designed to be launched with [kind](https://kind.sigs.k8s.io/docs/user/quick-start)
=============================================

Dependencies:
* kind
* kubectl
* terminal

```
cd /tmp/; git clone https://github.com/jdautomate/interview-web-app.git
cd interview-web-app
kind create cluster
kubectl apply -k .
```
