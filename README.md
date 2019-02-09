# Vagrant shared Files from host machine

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/d5de7c99d37e425e829b828b0729b97c)](https://app.codacy.com/app/ankurpatel18/Vagrant-shared-Files?utm_source=github.com&utm_medium=referral&utm_content=ankurpatel18/Vagrant-shared-Files&utm_campaign=Badge_Grade_Settings)

Sharing folders to vagrant machines from host machine.

### Steps to follow
 - Download sourcode from git and change directory to Vagrant-shared-Files
    ```sh
    git clone https://github.com/ankurpatel18/Vagrant-shared-Files.git
    cd Vagrant-shared-Files
    ```
 - You will find two folders 
    - ###### Donotshare -> which has sharing files for vagrant machines
    - ###### SharingBetweenVagrant -> vagrant machines
 - Change directory to using 
    ```sh
    cd SharingBetweenVagrant
    ```
- Start Vagrant machines
- Use SSH to go inside vagrant machine 
    ```sh
    vagrant ssh server1 
        or
    vagrant ssh server2
    ```
- go inside "sharedFolder" on user's directory
    ```sh
    cd sharedFolder
    ```
- Where you will find "Donotshare" folder files using 
    ```sh
    ls -la 
    ```
