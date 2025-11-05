# Pit Docker
## Quick start
1. Install Docker Engine with `apt` (not the VM Docker Desktop)**:** https://docs.docker.com/engine/install/ubuntu/#prerequisites
2. Install VSCode Dev Containers extension - https://code.visualstudio.com/docs/devcontainers/containers
3. Pull git submodules with 
   ```
   git submodule update --init --recursive
   ```

4. Open VS Code Command Palette (**CTRL + P**), type `>Dev Containers: Reopen in Container`, and select it
5. VS Code will open a new window that contains an integrated IDE inside the Docker container, according to the instructions inside `.devcontainer`