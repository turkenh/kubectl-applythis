# kubectl-applythis

A simple kubectl plugin that allows to create/apply Kubernetes resources directly from editor.

## Usage

```
  kubectl applythis
```

This will open the editor defined by your KUBE_EDITOR, or EDITOR environment variables, or fall back to 'vi'.
Once text editor opens, enter/paste your yaml and save the file. It will be applied to your Kubernetes cluster.

[![demo](https://asciinema.org/a/TEbs5i5ViC7tdNXU8Xcgw2HVd.svg)](https://asciinema.org/a/TEbs5i5ViC7tdNXU8Xcgw2HVd)