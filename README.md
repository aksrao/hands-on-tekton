# hands-on-tekton
learning tekton from scratch

Pre-requisite:-
- familiar with kubernetes and yaml
- install tekton cli (https://tekton.dev/docs/cli/#installation)
- deploy the tekton on k8s cluster (kubectl apply --filename \https://storage.googleapis.com/tekton-releases/pipeline/latest/release.yaml)
- namespace will be created named "tekton-pipelines"
- switch to the namespace "kubectl config set-context --current --namespace=tekton-pipelines"