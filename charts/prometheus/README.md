
```sh
module "prometheus" {
source = "git@github.com:clouddrove/terraform-monitoring-prometheus.git"

  secretName = ""
  kubernetesendpoint = ""

  namespace = ""
  prometheus_ingress_endpoint = ""
  alertmanager_ingress_endpoint = ""
  
}

```
