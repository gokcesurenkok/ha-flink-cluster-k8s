### High Available Flink Cluster on Kubernetes

This includes all kubernetes resources necessary for flink cluster installation

Before applying the yamls please modify them with your zookeeper and hdfs setup

then first apply configmaps

```kubectl create -f ./configmap/ ```

then services

```kubectl create -f ./services/ ```
then lastly the deployments

```kubectl create -f ./deployment/ ```

