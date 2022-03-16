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

Projects catalog
----------------

You may want to take a look at the [index.yaml](https://riotkit-org.github.io/helm-of-revolution/index.yaml), or import the repository from shell and perform `helm search repo riotkit`

- https://github.com/riotkit-org/backup-repository
- https://github.com/riotkit-org/br-backup-controller
- https://github.com/riotkit-org/br-backup-maker
- https://github.com/riotkit-org/flarum-container
- https://github.com/riotkit-org/infracheck
- https://github.com/riotkit-org/smtp-ext-relay
