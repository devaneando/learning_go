# Workspace

## Basic setup

Decide the folder where you want to have go (_in my case, `${HOME}/Development/Go`). It needs to have three subfolders:

- **bin**: Where the binary and compiled files will be stored.
- **pkg**: Where package archived folders will be stored, so they won't need to be recompiled everytime you build a new version.
- **src**: The source structure where the "_namespaced_" classes will be stored, usually following a "domain", "user", "project" hierarchy.
    - **github.com**: The domain part of the namespace.
        - **devaneando**: The user part of the namespace.
            - **my_project**: The project part of the namespace.
                - **my_folder**: The folder structure part of the namespace.
