# helm-of-revolution

Artifactory for FOSS software created by Riotkit, a grassroot libertarian tech collective.

Usage
-----

### helm

```bash
helm repo add riotkit-org https://riotkit-org.github.io/helm-of-revolution/
helm repo update
```

### helmfile

```yaml
repositories:
- name: riotkit
  url: https://riotkit-org.github.io/helm-of-revolution/
```
