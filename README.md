# vscode-remote-template

This project created templates for using **[VS Code Remote - Containers](https://aka.ms/vscode-remote/containers)** extension by language.

## Setting up the development container

Follow these steps to open this sample in a container:

1. If this is your first time using a development container, please follow the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).

2. **Linux users:** Update `USER_UID` and `USER_GID` in `.devcontainer/Dockerfile` and `"runArgs": [ "-u": "1000" ]` in `.devcontainer/devcontainer.json` with your user UID/GID if not 1000 to avoid creating files as root.

3. If you're not yet in a development container:
  - Copy **`.devcontainer` dir** for your language to repository root.
    - Copy the `.vscode` if necessary.
  - Update repository information in `.devcontainer/devcontainer.json`.
  - Press <kbd>F1</kbd> and select the **Remote-Containers: Open Folder in Container...** command.
  - Select your repository, wait for the container to start, and try things out!
