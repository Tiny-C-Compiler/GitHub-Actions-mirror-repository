# mirror-repositry-github-actions
The source code is Mirrored from https://repo.or.cz/w/tinycc.git

Guide on using SSH keys to setup Mirroring.

1. Generate SSH Key using any tool.  
   *  Recommended: to download and use ssh-keygen tool.  
   * Can be done online. 
  https://8gwifi.org/sshfunctions.jsp  
  Caution: online website can steal your generated SSH key,  
  ![image](https://user-images.githubusercontent.com/21064622/191988520-98b9284f-1225-45fc-b8f3-43ea5b660dc7.png)
  
2. Place the generated Public Key into Repository to access it.
3. Insert Private Key as Actions Repository Secret in the script running repository, so it would use it and gain access.
