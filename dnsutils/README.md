https://kubernetes.io/docs/tasks/administer-cluster/dns-debugging-resolution/

kubectl apply -f pod.yaml

kubectl exec -i -t dnsutils -- /bin/sh
