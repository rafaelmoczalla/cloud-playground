# Cloud Playground
A playground for local hands on sessions for teaching software developement for cloud.

## Prerequisits
This project requires Docker Desktop to be installed.

## Quickstart
Start the cluster.
```bash
docker compose up -d
```

Next export the kubeconfig & check if the nodes are running.
```bash
export KUBECONFIG=./kubeconfig/k3s.yaml
kubectl get nodes
```

## License
Full copyright belongs to me Rafael Moczalla.
