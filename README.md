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


### Visual tutorial for Actions repository to gain access to mirror-repository
As mentioned you use any SSH key generator. (Example: https://8gwifi.org/sshfunctions.jsp)
And you do this, remember to trigger workflow, it should all work.
![image](https://github.com/user-attachments/assets/1542b854-05de-4ca6-9e5c-69c1f9848d76)
![image](https://github.com/user-attachments/assets/ca77b5fc-2a2e-41eb-8911-3a29d054bbf3)

