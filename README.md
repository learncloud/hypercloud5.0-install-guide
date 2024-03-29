# HyperCloud 5.0 Install Guide Navigator


### Module (Required)

| Module                            | Version                                                         | URL                                                              | ETC |
| --------------------------------- | --------------------------------------------------------------- | ---------------------------------------------------------------- | --- |
| OS & Packages                     | ProLinux8.2                                                     | https://github.com/learncloud/build-local-repo-prolinux8.2       |     |
| External DNS                      |                                                                 |                                                                  |     |
| Podman  (docker 대체제)            |     https://github.com/tmax-cloud/install-registry/blob/5.0/podman.md                                                            |                                                                  |     |
| Image Registry - Docker           | Docker version 20.10.12                                         | https://github.com/learncloud/install-registry-docker-ce         |     |
| Kubernetes & CRI-O                | 1.19.1, 1.19.4                                                  | https://github.com/learncloud/install-k8s-5.0                    |     |
| CSI - NFS                         |                                                                 | https://github.com/learncloud/install-nfs-5.0                    | Prometheus를 구축하기 위한 선행 단계 |
| CNI - Calico                      | 3.16.6                                                          | https://github.com/learncloud/k8srepo/tree/main/v5.0/install-cni-5.0    |     |
| Cert Manager                      | v1.5.4                                                          | https://github.com/learncloud/k8srepo/tree/main/v5.0/install-cert-manager     |     |
| Ingress Controller - nginx        | 0.33.0                                                          | https://github.com/learncloud/k8srepo/tree/main/v5.0/install-ingress-5.0 |     |
| Helm Operator                     |                                                                 | https://github.com/learncloud/k8srepo/tree/main/v5.0/install-helm-operator-5.0|     |
| Prometheus                        | v2.11.0                                                         | https://github.com/learncloud/install-prometheus-5.0             |     |
| MetalLB                           | v0.9.3                                                          | https://github.com/learncloud/install-metallb-5.0                | HyperAuth, Console을 구축하기 위한 선행 단계 |
| HyperAuth                         | b1.1.1.37                                                       | https://github.com/learncloud/install-hyperauth-5.0              |     |
|  API Gateway, Operator            | v5.0.26.6, v5.0.25.16                                           | https://github.com/learncloud/install-hypercloud-5.0             |     |
| HyperCloud Console, Operator      | 0.5.1.32, 5.1.0.1                                               | https://github.com/learncloud/install-console-5.0                |     |
| CSI - Ceph                        |                                                                 |                                                                  | Hyper Cloud v5.0에서는 권장 X    |

<br><br>
### Module (Recommended)
| Module                            | Version                                                         | URL                                                              | ETC |
| --------------------------------- | --------------------------------------------------------------- | ---------------------------------------------------------------- | --- |
| Image Registry - HyperRegistry    |                                                                 | https://github.com/learncloud/HyperRegistry-Chart-5.0            | CI/CD를 구축하기 위한 선행 단계   |
| Helm                              | v3                                                              | https://github.com/learncloud/install-helm-v3.0                  | CI/CD를 구축하기 위한 선행 단계   |
| Catalog Controller                | v0.3.0                                                          | https://github.com/learncloud/install-Catalog-Controller-5.0     | gitlab설치를위한 선행 단계   |
| Template ServiceBroker            | 0.1.3                                                           | https://github.com/learncloud/install-tsb-5.0                    | gitlab설치를위한 선행 단계   |
| GitLab                            |                                                                 |https://github.com/learncloud/install-gitlab-5.0                  | CI/CD를 구축하기 위한 선행 단계   | 
| CI/CD Catalog                    |  | https://github.com/learncloud/bulid-tekton-cicd-catalog/tree/main/was/_common        | CI/CD를 구축하기 위한 선행 단계 |
| Tekton CI/CD                      | Pipeline: v0.26.0 <br> Trigger: v0.15.0 <br> CI/CD Operator: v0.4.2 | https://github.com/learncloud/install-tektoncicd-5.0        | |
| Istio                    | v1.5.1               | 파일 넣어야함, 그리고 원본 깃헙에 오타잇음 (jaeger~라고 치환해야하는데 jager라고 잘못 치환하는 )                   |     |


<br><br><br><br><br><br><br><br><br><br><br>
# 아래는 아직 미완성 

### Module (Recommended)
| Module                            | Version                                                         | URL                                                              | ETC |
| --------------------------------- | --------------------------------------------------------------- | ---------------------------------------------------------------- |---- |
| Registry Operator                 | v0.3.1                                                          | https://github.com/tmax-cloud/install-registry-operator/tree/5.0 |
| CAPI                              | v0.3.6                                                          | https://github.com/tmax-cloud/install-capi/tree/5.0              |
| KubeFed                           | v0.3.0                                                          | https://github.com/tmax-cloud/install-federation/tree/5.0        |
| AWX Operator                      |                                                                 |                                                                  |


# 아래는 아직 미완성 


### Module (Optional)
| Module                   | Version              | Guide                                                                   |     |
| ------------------------ | -------------------- | ----------------------------------------------------------------------- | --- |
| Grafana                  | 6.4.3                | https://github.com/learncloud/install-grafana-5.0                       | readme공사중    |
| Kiali                    | 1.21                 | https://github.com/tmax-cloud/install-kiali/tree/5.0                    |     |
| NetworkAgent             | v0.4.2               | https://github.com/tmax-cloud/install-networkagent/tree/5.0             |     |
| NetworkWebhook           | 0.1.3                | https://github.com/tmax-cloud/install-networkwebhook/tree/4.1           |     |
| Nvidia GPU               |                      | https://github.com/tmax-cloud/install-nvidia-gpu-infra/tree/5.0         |     |
| KubeFlow                 | v1.0.2               | https://github.com/tmax-cloud/install-ai-devops/tree/main               |     |
| EFK                      | 7.2.0, v1.4.2, 7.2.0 | https://github.com/tmax-cloud/install-EFK/tree/5.0                      |     |
| ChartMuseum              |                      | https://github.com/tmax-cloud/install-helm-repository/tree/master       |     |
| ovirt                    | 4.4.3                | https://github.com/tmax-cloud/install-ovirt/tree/main                   |     |
| OLM                      | 0.15.1               | https://github.com/tmax-cloud/install-OLM/tree/main                     |     |
| clair                    | ???                  | https://github.com/tmax-cloud/install_clair/tree/main                   |     |
| velero                   | 1.4.2                | https://github.com/tmax-cloud/install-velero/tree/main                  |     |
| CAPI-provider-aws        | v0.5.5-alpha.0       | https://github.com/tmax-cloud/install-CAPI/tree/5.0                     |     |
| registry-operator        | v0.3.1               | https://github.com/tmax-cloud/install-registry-operator/tree/5.0        |     |
| image-validating-webhook | ???                  | https://github.com/tmax-cloud/install-image-validating-webhook/tree/5.0 |     |
| HAProxy & Keepalived     | 1.5.18, 1.3.5        | https://github.com/tmax-cloud/install-haproxy/tree/5.0 | |

