- # How can I update system?
``sudo pacman -Syu``

- # How can I install a package?
``sudo pacman -S package``

- # How can I remove a package?
``sudo pacman -R package``

- # How can I remove a package and its dependencies that are no longer needed by other packages?
``sudo pacman -Rs package``

- # Install the ufw (Uncomplicated Firewall)
``sudo pacman -S ufw``

- # Enable the firewall 
 ``sudo ufw enable``
 
 **Extra Steps if you want:**
 *By default, ufw allows all incoming and outgoing traffic, you can add specific rules to the firewall to block or allow specific connections.*
 ``sudo ufw allow ssh``
 
 ``sudo ufw status verbose``
