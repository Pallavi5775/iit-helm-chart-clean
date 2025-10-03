# Helm chart for iiT ingestion stack

Use `helm install iit ./` with values overridden as needed.
helm repo add iit https://Pallavi5775.github.io/iit-helm-chart
helm repo update
helm install iit iit/iit-stack -n iit --create-namespace