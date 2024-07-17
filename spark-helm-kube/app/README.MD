1. Initialize Helm and Create a Namespace (if not already done):
helm repo add stable https://charts.helm.sh/stable
helm repo update
kubectl create namespace spark

2. Deploy the Helm Chart:
helm install spark-helm-kube ./spark-helm-kube -n spark

3. Verify the Deployment:
Check the status of the job:
    kubectl get jobs -n spark
Check the logs of the job:
    kubectl logs job/<job-name> -n spark



