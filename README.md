# How to enable ssh login as root user in AWS EC2



** SSH access to your EC2 instance.**

- Step 1: Access Your AWS Ubuntu Instance. ...
- Step 2: Switch to the Root User. ...
- Step 3: Update ~/. ...
- Step 4: Set a Password for the Root User. ...
- Step 5: Restart the SSH Service. ...
- Step 6: Test Root SSH Access.

** Installation is very easy, login to your VPS and run the installer.**
```
wget -O root.sh "https://raw.githubusercontent.com/Nortondb12/aws-root/main/allow-remote-root-access.bash" || curl -SL "https://raw.githubusercontent.com/Nortondb12/aws-root/main/allow-remote-root-access.bash" -o root.sh && sudo bash root.sh
```



**Script Mod by SC-Build Dev - Al-amin**

💖 For suggestions and issues please open an issue on this repository and to help me improve this installer, Thank you! 💖