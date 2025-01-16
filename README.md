# nonmem_workbench
nonmem devcontainer on VSCode.

# Instruction
1. Execute [VSCode](https://code.visualstudio.com/)
1. Add a valid **nonmem.lic** file to [.devcontainer Folder](.devcontainer).
1. Open Folder 
    - Navigate to the top menu: **File > Open Folder...**
1. install the [devcontainer extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
1. Open Command Palette
    - Navigate to the top menu: **View > Command Palette...**
1. then Execute **Dev Containers: Reopen in Container**

# Update
If you want to build the Docker Image yourself, you need to update [the version numbers](.devcontainer/docker-compose.yml#L6-L12).