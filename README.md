# GitOps Dynamic Web App with Sidecar Pattern (OpenShift & Argo CD)

This repository contains an example of a **dynamic web application deployed using GitOps with Argo CD** on Red Hat OpenShift.  
The application demonstrates a Sidecar Sync Pattern, where UI content updates without restarting pods, while keeping the application stateless and using only Red Hat provided container images.

---

## Key Features

- Stateless dynamic web application
- UI updates instantly when content changes in Git
- No pod restarts required
- Uses official Red Hat UBI images from `registry.access.redhat.com`
- Demonstrates real GitOps workflow with **diff → sync → update**
- Uses a sidecar container to sync ConfigMap updates into a shared volume
