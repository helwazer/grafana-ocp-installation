Explanation of Each Part:
1- Grafana Operator Deployment (grafana-operator-deployment.yaml):

2- Deploys the Grafana operator, which will manage Grafana instances based on the Grafana custom resource.
Grafana Custom Resource (grafana-cr.yaml):

3- Defines a Grafana instance with configuration such as authentication settings, ingress rules, and the Grafana version to deploy.
Secret for Admin Credentials (grafana-admin-secret.yaml):

4- Creates a Kubernetes secret with the base64 encoded values for the Grafana admin username and password.
Route to Expose Grafana (grafana-route.yaml):

5- Exposes the Grafana service via an OpenShift route, making it accessible externally at the specified hostname.
