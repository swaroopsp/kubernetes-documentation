# kubernetes-documentation

## Commands
- `skaffold run` - For build and run
- `kubectl apply -f config.yaml` - For applying the ConfigMap changes
- `kubectl describe configmap config-example` - For describing the contents of Config Map
- `kubectl logs <pod_name> -f` - For tailing the logs from the pod

## Additional Commands
- `kubectl get pod` - To get the pod
- `kubectl describe configmap config-example` - To see the config map
- `kubectl logs config-example-6bf8c6c45-ffbb8 -f` - To see the logs
- `kubectl apply -f config.yaml` - To apply the new config
- `kubectl delete daemonsets,replicasets,services,deployments,pods,rc,ingress --all --all-namespaces` - To delete all pods
