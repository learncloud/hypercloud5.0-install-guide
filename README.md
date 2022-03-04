# HyperCloud 5 Install Guide Navigator

### Module (Required)
| Module                            | Version                                                         | URL                                                              | ETC |
| --------------------------------- | --------------------------------------------------------------- | ---------------------------------------------------------------- | --- |
| OS & Packages                     | ProLinux8.2                                                     | https://github.com/learncloud/build-local-repo-prolinux8.2       |     |
| External DNS                      |                                                                 |                                                                  |     |
| Image Registry - Docker           | Docker version 20.10.12                                         | https://github.com/learncloud/install-registry-docker-ce         |     |
| Kubernetes & CRI-O                | 1.19.1, 1.19.4                                                  | https://github.com/learncloud/install-k8s-5.0                    |     |
| CNI - Calico                      | 3.16.6                                                          | https://github.com/learncloud/k8srepo/tree/main/v5.0/install-cni-5.0    |     |
| Cert Manager                      | v1.5.4                                                          | https://github.com/learncloud/k8srepo/tree/main/v5.0/install-cert-manager     |     |
| Ingress Controller - nginx        | 0.33.0                                                          | https://github.com/learncloud/k8srepo/tree/main/v5.0/install-ingress-5.0 |     |
| Helm Operator                     |                                                                 | https://github.com/learncloud/k8srepo/tree/main/v5.0/install-helm-operator-5.0|     |
| CSI - NFS                         |                                                                 | https://github.com/learncloud/install-nfs-5.0                    | 구축하기 위한 선행 단계     |
| Prometheus                        | v2.11.0                                                         | https://github.com/learncloud/install-prometheus-5.0             |     |
| MetalLB                           | v0.9.3                                                          | https://github.com/learncloud/install-metallb-5.0                |     |
| HyperAuth                         | b1.1.1.37                                                       | https://github.com/learncloud/install-hyperauth-5.0              |     |
|  API Gateway, Operator            | v5.0.26.6, v5.0.25.16                                           | https://github.com/learncloud/install-hypercloud-5.0             |     |
| HyperCloud Console, Operator      | 0.5.1.32, 5.1.0.1                                               | https://github.com/learncloud/install-console-5.0                |     |
| CSI - Ceph                        |                                                                 |                                                                  |     |

<br><br>
### Module (Recommended)
| Module                            | Version                                                         | URL                                                              | ETC |
| --------------------------------- | --------------------------------------------------------------- | ---------------------------------------------------------------- | --- |
| Image Registry - HyperRegistry    |                                                                 | https://github.com/learncloud/HyperRegistry-Chart-5.0            | CI/CD를 구축하기 위한 선행 단계   |



<br><br><br><br><br><br><br><br><br><br><br>
# 아래는 아직 미완성 

### Module (Recommended)
| Module                            | Version                                                         | URL                                                              |
| --------------------------------- | --------------------------------------------------------------- | ---------------------------------------------------------------- |
| GitLab                            |                                                                 |                                                                  |
| Template ServiceBroker            | 0.1.3                                                           | https://github.com/tmax-cloud/install-tsb/tree/tsb-5.0           |
| Catalog Controller                | v0.3.0                                                          | https://github.com/tmax-cloud/install-catalog/tree/5.0           |
| Tekton CI/CD                      | Pipeline: v0.26.0<br>Trigger: v0.15.0<br>CI/CD Operator: v0.4.2 | https://github.com/tmax-cloud/install-tekton/tree/5.0            |
| Registry Operator                 | v0.3.1                                                          | https://github.com/tmax-cloud/install-registry-operator/tree/5.0 |
| CAPI                              | v0.3.6                                                          | https://github.com/tmax-cloud/install-capi/tree/5.0              |
| KubeFed                           | v0.3.0                                                          | https://github.com/tmax-cloud/install-federation/tree/5.0        |
| AWX Operator                      |                                                                 |                                                                  |


# 아래는 아직 미완성 


### Module (Optional)
| Module                   | Version              | Guide                                                                   |
| ------------------------ | -------------------- | ----------------------------------------------------------------------- |
| Grafana                  | 6.4.3                | https://github.com/tmax-cloud/install-grafana/tree/5.0                  |
| Istio                    | v1.5.1               | https://github.com/tmax-cloud/install-istio/tree/5.0                    |
| Kiali                    | 1.21                 | https://github.com/tmax-cloud/install-kiali/tree/5.0                    |
| NetworkAgent             | v0.4.2               | https://github.com/tmax-cloud/install-networkagent/tree/5.0             |
| NetworkWebhook           | 0.1.3                | https://github.com/tmax-cloud/install-networkwebhook/tree/4.1           |
| Nvidia GPU               |                      | https://github.com/tmax-cloud/install-nvidia-gpu-infra/tree/5.0         |
| KubeFlow                 | v1.0.2               | https://github.com/tmax-cloud/install-ai-devops/tree/main               |
| EFK                      | 7.2.0, v1.4.2, 7.2.0 | https://github.com/tmax-cloud/install-EFK/tree/5.0                      |
| Helm                     | v3                   | https://github.com/tmax-cloud/install-helm/tree/master                  |
| ChartMuseum              |                      | https://github.com/tmax-cloud/install-helm-repository/tree/master       |
| ovirt                    | 4.4.3                | https://github.com/tmax-cloud/install-ovirt/tree/main                   |
| OLM                      | 0.15.1               | https://github.com/tmax-cloud/install-OLM/tree/main                     |
| clair                    | ???                  | https://github.com/tmax-cloud/install_clair/tree/main                   |
| velero                   | 1.4.2                | https://github.com/tmax-cloud/install-velero/tree/main                  |
| CAPI-provider-aws        | v0.5.5-alpha.0       | https://github.com/tmax-cloud/install-CAPI/tree/5.0                     |
| registry-operator        | v0.3.1               | https://github.com/tmax-cloud/install-registry-operator/tree/5.0        |
| image-validating-webhook | ???                  | https://github.com/tmax-cloud/install-image-validating-webhook/tree/5.0 |
| HAProxy & Keepalived     | 1.5.18, 1.3.5        | https://github.com/tmax-cloud/install-haproxy/tree/5.0 |
