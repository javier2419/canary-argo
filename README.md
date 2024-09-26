kubectl api-resources | grep rollout

kubectl argo rollouts list rollouts -n apache
kubectl argo rollouts get rollouts apache-ro -n apache