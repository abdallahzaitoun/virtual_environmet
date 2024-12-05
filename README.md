# virtual_environmet
Create and Activate a Virtual Environment

## Create a Virtual Environment:
```
python3 -m venv <virtual_env_name>
```
## Activate the Virtual Environment: 
```
source <virtual_env_name>/bin/activate
```
Now, I can install Packages i need to deal with pip commands

## Install Packages: 
```
pip install <package_name>
```
for example in jenkins working to install jenkins-cli to deal with in your terminal
```
pip install jenkins-cli
```
To deal with Jenkins-cli after downloading the package, you should authenticate your jenkins accout as
```
curl -L https://github.com/jenkins-zh/jenkins-cli/releases/latest/download/jcli-linux-amd64.tar.gz|tar xzv
sudo mv jcli /usr/local/bin/
```
