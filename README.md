# Kubernetes_3-Tier_Web

k8s-3tier-app/
├── README.md
├── backend/
│   ├── deployment.yaml
│   ├── service.yaml
│   ├── configmap.yaml
│   └── secret.yaml
├── database/
│   ├── statefulset.yaml
│   ├── service.yaml
│   ├── pvc.yaml
│   └── secret.yaml
└── ingress/
    └── ingress.yaml
scripts/
  install.sh
  deploy.sh
  test.sh
  cleanup.sh
