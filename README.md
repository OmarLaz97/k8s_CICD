# k8s_CICD
## _Kubernetes configurations for my CICD project_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Features

- Deploy a kubernetes cluster over aws

## Installation

The application requires [minikube](https://minikube.sigs.k8s.io) to run

## Run the app

The application is very easy to run.

Just by running a single command you will be able to create and deploy the application using minikube on your local machine.
Make sure that you have a running minikube cluster

```sh
cd k8s_CICD
kubectl apply -f ./k8s
```

This will create a minikube cluster with the application running on it and you can access it using the minikube ip
```sh
minikube ip
```


Verify the deployment by navigating to your server address in
your preferred browser.

```sh
<minikube ip>
```

