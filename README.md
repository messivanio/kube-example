kube-example
============

Just a [kustomize](https://kustomize.io/) example.


## How To Install

Use [asdf](https://github.com/asdf-vm/asdf) to install everything you need.

```bash
# Clone this repository
$ git clone git@github.com:messivanio/kube-example.git

# Go into the repository
$ cd kube-example

# Install everything
$ asdf install
```

Otherwise, manually install [each tool version](.tool-versions).


## How To Use

```bash
# Go into the overlay
$ cd overlays/lab1
 
# Build and apply k8s resources
$ kustomize build . | kubectl apply -f -
```
