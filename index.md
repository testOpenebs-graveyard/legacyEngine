# Helm Repository for legacyEngines testing

## Installation Guide

### Add the repository

```bash
helm repo add legacyEngine https://testopenebs.github.io/legacyEngine/ 
```

### Install chart

```bash
helm install legacy-engine legacyEngine/legacy-engine -n legacy-engine --create-namespace
```