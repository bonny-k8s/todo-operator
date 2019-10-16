# TodoOperator

This is an example operator built using the [Bonny Kubernetes Extension Framework](https://github.com/coryodaniel/bonny).

Notes:

* dev environment uses your default kubernetes context
* test environment stubs kubernetes interaction


Deploy it to your cluster!

```bash
kubectl apply -f manifest.yaml
kubectl apply -f todo.yaml
kubectl get todo/have-fun -o yaml
```