# Typescript & Node 12 LTS

See VS Code container configuration at https://github.com/microsoft/vscode-dev-containers/tree/v0.134.1/containers/typescript-node

Customizations:
* Uses ZSH as Shell
* Runs as the `node` user rather than `root`
* Uses postCreateCommand to install project dependencies using yarn
* Forwards port 3000 to the host system
* Installs Editorconfig extension