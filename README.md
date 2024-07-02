# nonmem_workbench
nonmem devcontainer on VSCode.

# Instruction
1. change the [nonmem.lic](.devcontainer/nonmem.lic) to a real license file. the current file is fake.
2. In VSCode, Open Command Pallete(<kbd>F1</kbd>) and then Execute "Dev Containers: Reopen in Container"

# Update
If you want to update the software, you have to change the version numbers.

[dockerfile](.devcontainer/dockerfile#L1)

[docker-compose.yml](.devcontainer/docker-compose.yml#L6-L12)

And Refer to a PsN installation document [document](https://uupharmacometrics.github.io/PsN/install.html)