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

8. Download [Docker for Windows](https://desktop.docker.com/win/stable/amd64/Docker%20Desktop%20Installer.exe?utm_source=docker&utm_medium=webreferral&utm_campaign=dd-smartbutton&utm_location=header)

9. Download [VS Code](https://code.visualstudio.com/sha/download?build=stable&os=win32-x64-user)

10. Config Git

    ``` git
    git config --global user.name "John Smith"
    git config --global user.email "johnsmith@example.com"
    ```

11. Generate SSH Key

    ```
    ssh-keygen -t ed25519 -C "johnsmith@example.com"
    ```

11. Install FiraCode Font (Optional)

13. Install [Beekeeper Studio](https://www.beekeeperstudio.io/download/?ext=exe&arch=&type=installer) / [dBeaver](https://dbeaver.io/files/dbeaver-ce-latest-x86_64-setup.exe)

14. Install Valet for Windows

    ```
    composer global require cretueusebiu/valet-windows
    valet install
    ```

15. Change Directories into your project folder and run Valet Park

    ```
    mkdir code
    cd code
    valet park
    valet start
    ```

    

