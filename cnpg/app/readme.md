For the backups in cnpg install this:
kubectl apply -f \
        https://github.com/cloudnative-pg/plugin-barman-cloud/releases/download/v0.5.0/manifest.yaml

Upgrading it could be a good idea. If in doubt reinstall 0.5.0. If this is not available anymore use the manifest.yaml file in this repo.