# Happy Helming

## We need a Kubernetes cluster or a minikube 


## Install Helm CLI
checkout the  [Helm Official documentation](https://helm.sh/docs/intro/quickstart/).

```
cd Nautilus-helm
helm create nautilus-example
```

## Add K8s files to the Chart

Copy k8s files into our `nautilus-example/templates/` folder

## Test the template

```
helm template nautilus-example
```

## Install app using Chart
```
helm install nautilus-example
```

# list our releases
```
helm list
```

# upgrade our release
```
helm upgrade nautilus-example nautilus-example --values ./nautilus-example/values.yaml
```