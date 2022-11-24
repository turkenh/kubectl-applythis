# kubectl-applythis

A simple kubectl plugin that allows to create/apply Kubernetes resources directly from editor.

## Installation

```bash
# Download the release archieve.
curl -fsSL https://github.com/turkenh/kubectl-applythis/releases/download/v0.1.0/kubectl-applythis-v0.1.0.tar.gz | tar -xz
# Move it as a kubectl plugin
sudo mv kubectl-applythis/applythis /usr/local/bin/kubectl-applythis
# Clean up
rm -rf kubectl-applythis
```

## Usage

```
  kubectl applythis
```

This will open the editor defined by your KUBE_EDITOR, or EDITOR environment variables, or fall back to 'vi'.
Once text editor opens, enter/paste your yaml and save the file. It will be applied to your Kubernetes cluster.


https://user-images.githubusercontent.com/9900707/203765440-a38b9e3e-b553-44e5-ae34-455ead8d9e97.mp4

