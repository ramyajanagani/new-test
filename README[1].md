# Assessment Details

### Installing APP.

Note: Add docker registry secret into helm values file and kubernetes as well.
Install the helm chart.
``` helm install app ./ ```
The Traffic will be served via Ingress. 

If you are using nginx ingress add nginx annotiations in ingress template under helm folder.

### Stack:
- Helm
- Kubernetes
- Nginx