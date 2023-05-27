# kind

This is the repository for the unraid kind plugin.

<img src="https://git.panaetius.co.uk/dtomlinson91/unraid-kind/raw/branch/main/assets/unraid-kind.png" width="300px" />

## description

kind is a tool for running local Kubernetes clusters using Docker container “nodes”.
kind was primarily designed for testing Kubernetes itself, but may be used for local development or CI.

See the [git repository](https://github.com/kubernetes-sigs/kind) for bat for more information.

## dev

Drone builds the plugin source using cargo on a new tag creation.

Tag versions follow bat releases.
