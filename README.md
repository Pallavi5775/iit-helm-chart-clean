# Helm chart for iiT ingestion stack

Use `helm install iit ./` with values overridden as needed.
helm repo add iit https://pallavi5775.github.io/iit-helm-chart
helm repo update
helm install iit iit/iit-stack -n iit --create-namespace


helm repo index docs --url https://pallavi5775.github.io/iit-helm-chart
git add docs/index.yaml
git commit -m "Fix Helm repo URL casing"
git push origin  main
