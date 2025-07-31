# Container Overview
This Devcontainer is for Fullstack Development. See list of features below.

## List of Features
- "image" and "build" options
  - Recommend to only use "build" option to run DocKerfile before vscode processes to manage system dependencies
- VS Code Extensions
  - Extension Pack for Java | vscjava.vscode-java-pack
  - Python | ms-python.python
  - Angular Language Service | Angular.ng-template
    - Requires NPM?
  - Spring Boot Extension Pack | vmware.vscode-boot-dev-pack
- Port Extensions
  - ???

## Raw JSON
{
    "image": "mcr.microsoft.com/devcontainers/typescript-node",
    "build": {"dockerfile": "Dockerfile"},
    "customizations": {
        "vscode": {
            "extensions": [
                "vscjava.vscode-java-pack",
                "ms-python.python",
                "Angular.ng-template",
                "vmware.vscode-boot-dev-pack"
            ]
        }
    },
    "forwardPorts": [4200]
}