# Vagrant shared Files from host machine
Sharing folders to vagrant machines from host machine.

### Steps to follow
 - Download sourcode from git
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
