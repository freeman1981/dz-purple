## Commands

```shell
kubectl get pods
```

```shell
kubectl describe pods <pod-name>
```

```shell
kubectl describe pods short-app
```

```shell
kubectl delete pods short-app
```

```shell
kubectl get services
```

```shell
kubectl get all
```

```shell
minikube service <service-name> --url
```

```shell
minikube service short-app-port --url
```

## sql

```sql
CREATE TABLE "Link" (
  "id" SERIAL NOT NULL,
  "url" TEXT NOT NULL,
  "hash" TEXT NOT NULL,

  CONSTRAINT "Link_pkey" PRIMARY KEY ("id")
);
```


```shell
sudo minikube tunnel
```

```shell
kubectl port-forward <pod>
```

