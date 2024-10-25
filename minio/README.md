To deploy run:
 ```kubectl kustomize . | kubectl apply  -f -```

 Don't forget to populate the secret from Bitwarden. Reason: Not decryptable by sealed-secrets due to special chars.