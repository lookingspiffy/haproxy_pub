Once keepalived is installed, both files will be revised and placed in /etc/keepalived/

**Note for keepalived.conf**

During configuration please check if you have eth1 available and broadcasting, which is what the default template is set to use. If you do not, edit the eth1 entry and change it to the interface you have, whether another eth, ens, or other.
