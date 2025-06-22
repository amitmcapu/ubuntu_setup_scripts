### Install Curl 

```
sudo apt update
sudo apt install curl
```

### Install Python and pip

```
sudo apt update
sudo apt install python3 python3-pip -y

python3 --version
```


### Install NVM and NodeJS

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash

export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

nvm --version                                 # Check current version

```

### After installation finishes, run:
```
source ~/.bashrc


nvm install v22.16.0

nvm use v22.16.0 # Activate it 

nvm alias default v22.16.0                     # Now anytime you open a terminal, v22.16.0 will be the active Node.js version.
```

## Install Brave Browser 
```
curl -fsS https://dl.brave.com/install.sh | sh

brave-browser --version
```

## Install Visual Studio code | Google Chrome | Postman | VLC

- From Ununtu Store / App Center

## Install Terminator

```
sudo apt-get update
sudo apt-get install terminator
```

## Add Github SSH keys 

```
ssh-keygen -t rsa -b 4096 -C "amit.mca.pu@gmail.com"     # Generate a new SSH key pair

eval "$(ssh-agent -s)"                                   # Start SSH agent

ssh-add ~/.ssh/id_rsa                                    # Add your private key to SSH agent

cat ~/.ssh/id_rsa.pub                                    # Copy your public key to clipboard
                                
https://github.com/settings/keys                         # Add your SSH key here in github

```




