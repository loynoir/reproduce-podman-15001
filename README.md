### What
A try, to start vscode devcontainer using `podman` instead of `docker`.

### Folder Structure
`.devcontainer` is generated from vscode.

### Reproduce
`Ctrl + Shift + P` add below to `settings.json`

`"remote.containers.dockerPath": "podman"`

### Link
https://github.com/containers/podman/issues/15001