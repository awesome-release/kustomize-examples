# kustomize-examples

Example private repo using for testing Release's Kustomize support

To test outside Release:

```
cd hello-world/overlays/ephemeral-remote
kustomize edit set configmap the-map --from-literal="greeting=Hello from ephemeral environment"
kustomize build .
```
