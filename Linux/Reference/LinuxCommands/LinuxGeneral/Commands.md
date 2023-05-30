
- ## Enable trim operations on SSD/NVME
*If you have an SSD or NVME, it would be highly recommended to enable fstrim to ensure your SSD or NVME stays in good working condition.*

``sudo systemctl enable --now fstrim.timer``


- ## Enable the firewall 
 ``sudo ufw enable``
 
 **Extra Steps if you want:**
 *By default, ufw allows all incoming and outgoing traffic, you can add specific rules to the firewall to block or allow specific connections.*
 ``sudo ufw allow ssh``
 
 ``sudo ufw status verbose``
