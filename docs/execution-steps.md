## Kubernetes Context Project Execution

### Dev Context
Context: dev
Namespace: dev

Commands:
kubectl config use-context dev
kubectl apply -f nginx-dev.yaml
kubectl get pods

Result:
Nginx running in dev namespace.

---

### Prod Context
Context: prod
Namespace: prod

Commands:
kubectl config use-context prod
kubectl apply -f busybox-test.yaml
kubectl get pods

Result:
BusyBox running in prod namespace.
