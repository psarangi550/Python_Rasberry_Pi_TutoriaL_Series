# <ins> Rasberry Pi Installation Steps </ins> #

- First we need to Shut Down the `Rasberry Pi` from the Software Desktop
- Then we need to wait for 20 seconds and then remove the Power cable from the `Rasberry Pi`

### <ins> How to Connect to the Rasberry Pi using the SSH Connection </ins> ###

- In windows Version Less than `windows 10` then we don't Have Access to the `SSH` in that case we can install `putty` in order to connect to the `Rasberry Pi`

- we can connect to the Rasberry Pi by using the `using the username and password while installing the Rasberry Pi Operating System `

    ```
        ssh <username>@<ip Address Of Rasberry Pi>

        #here  it will ask for the fingureprint yes/No
        #Then it will Prompt for the Password that we set during the 
        installation of Rasberry Pi
    ```

- we can exit the `Rasberry Pi` Terminal After Connectiing to the Rasberry Pi using the command `exit`


### <ins> How to Set The Rasberry PI using the `VNC` which will perovide the Access of Rasberry Pi in the Own Local Desktop </ins> #

- we can set the `VNC` connection only after we set the `SSH Connection to the Rasberry PI Device`

- for Setting Up the `VNC` by using the following Steps

    - we need to write `sudo raspi-config` which will open the `Rasberry Pi` configuration in admin rights
    - Select the `interface option`
    - Select `VNC` and `select and enable` the Same thing
    - click on `finish` as the `VNC Server is configured`
    - once done we need to reboot the rasberry pi using the command as `sudo reboot`
    <br/><br/><br/>
    -  once the `Rasberry Pi` rebooted then connect to it again and use the command `sudo raspi-config` to open the `Rasberry Pi Configuration`
    - then select the option `System Options` &rarr; Select `Boot/Auto Login` &rarr; `B4 Desktop AutoLogin`
    - By default the `Rasberry Pi` will trying to do `B1 Console Login`
    - then select the `finish option` and then do the `reboot` by using the command as `sudo reboot` if not asking to `reboot preveiously`
    - if the `reboot taking longer` then  we can press the `Enter Key`

    <br/><br/><br/>

    - once the `Rasberry Pi` rebooted then connect to it again and use the command `sudo raspi-config` to open the `Rasberry Pi Configuration`
    - Select the Option as `Display Option` and Select the `VNC Resolution` select the `Resolution` as `Same as your Screen Resolution`
    - `1920X1080` stands for the `Full HD Resolution` Select that from the Option 
    - then select the `finish option` and then do the `reboot` by using the command as `sudo reboot` if not asking to `reboot preveiously`
    - if the `reboot taking longer` then  we can press the `Enter Key`

### <ins> How to Use VNC to connect to the Remote Desktop of Rasberry Pi </ins> ###

-  we need to install the `VNC Client` in order to connect to the `Rasberry Pi Desktop`
- go to the web browser and search for `vnc viewer realvnc` which will help in providing the `VNC client` to connect to the `Rasberry PI Desktop`

- Select the `Windows` as the `client` to download the `VNC viewer`

- Search for the `VNC Viewer` &rarr; FIle &rarr; New Connection &rarr; Provide the `Ip Address of the Rasberry Pi`

- provide the `username` and `password` for the `Rasberry Pi` in oprder to connect 






