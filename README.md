# Dev Environment Setup for Windows

## Packages

1. Install [Windows Terminal](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701)

2. Install [Chocolatey](https://chocolatey.org/)

3. Install PHP 

   ```
   choco install php 
   ```

4. Install Composer

   ``` 
   choco install composer
   ```

5. Install Node.js

   ```
   choco install nodejs
   ```

6. Install Git

   ```
   choco install git
   ```

7. Install MySQL

   ```
   choco install mysql
   ```

8. Download [WSL2 Linux KernelUpdate](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi)

9. Set default WSL version

   ```powershell
   wsl --set-default-version 2
   ```

10. Install [Ubuntu 20.04 LTS](https://www.microsoft.com/en-us/p/ubuntu-2004-lts/9n6svws3rx71?activetab=pivot:overviewtab)

11. Download [Docker for Windows](https://desktop.docker.com/win/stable/amd64/Docker%20Desktop%20Installer.exe?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=header)

12. Download [VS Code](https://code.visualstudio.com/sha/download?build=stable&os=win32-x64-user)

13. Config Git

    ``` git
    git config --global user.name "John Smith"
    git config --global user.email "johnsmith@example.com"
    ```

14. Generate SSH Key

    ```https://github.com/tonsky/FiraCode/releases/download/5.2/Fira_Code_v5.2.zip
    ssh-keygen -t ed25519 -C "johnsmith@example.com"
    ```

15. Install [FiraCode Font (Optional)](https://github.com/tonsky/FiraCode/releases/download/5.2/Fira_Code_v5.2.zip)

16. Install [Beekeeper Studio](https://www.beekeeperstudio.io/download/?ext=exe&arch=&type=installer) / [dBeaver](https://dbeaver.io/files/dbeaver-ce-latest-x86_64-setup.exe)

17. Install Valet for Windows

    ```
    composer global require cretueusebiu/valet-windows
    valet install
    ```

18. Change Directories into your project folder and run Valet Park

    ```
    mkdir code
    cd code
    valet park
    valet start
    ```

    

