# Jehebus's WoW Proxy Server (MachinaZero)

1. Download and Install Sockscap64 - https://www.sockscap64.com/homepage/

    Direct links: (download the setup.exe one)
    - https://www.mediafire.com/folder/32rj1769a2w82/v4.7
    - https://mega.nz/#F!qBoD2BiB!BZbHB1tetB79SAvJEoVlLw
    - https://www.dropbox.com/sh/yf88deqbe3m1xng/AAAiaAg6FR1uKtnBpcH5Gzv5a?dl=0
    
    It's compressed with 7zip, grab it [here](https://www.7-zip.org/download.html) if you need.
    
    Right click the downloaded 7z file and go to 7zip -> Extract Here
    
    ![Extract Here](extract.png)
    
    Run the SocksCap64-setup-4.7.exe file it creates and follow the install wizard.
    
2. [No] you don't want it to add your web browser, [Agree] to the terms
3. Click ![+ Apps](apps.png), find World of Warcraft in the list, tick it then click OK

   ![Example Game List](list.png)
5. Click ![Configure](configure.png), then go to the Network Rule tab
6. Click Add then click OK (all the boxes can remain blank)

   ![Weird add box with empty boxes](addbox.png)

   If it looks like this, hit OK again
   
   ![It should look like this](socks1.png)
   
6. We're done with setup, but Sockscap is in Administrator mode, we need it in Normal User mode.
   
   Click ![Exit](exit.png) (don't just close the window or it will just minimize to the tray)
7. Run SocksCap64(Normal User Mode)
8. Click ![Proxy](proxy.png)
9. Click the blue + on the left
10. Click in the list where it says Click to Edit IP, and enter machinazero.com
11. Click in the Account and Password boxes, entering your login details
    ![Example Proxy](proxylist.png)
12. Press Save

We're done! You can now run World of Warcraft via the icon inside SocksCap, and your connection will use the MachinaZero tunnel
