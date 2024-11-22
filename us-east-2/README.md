
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/ashutosh16/argocon-gitops-promoter-hydrate-demo.git
# cd into the cloned directory
git checkout 3b8f7de5dff184a6f1ecc4696c5dbc356e84299b
kustomize build ./user-configuration/production/us-east-2
```