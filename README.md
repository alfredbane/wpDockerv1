# wpDockerv1
Docker version for installing wordpress

## Install Docker on Ubuntu

### Step 1: Update Software Repositories
As usual, it’s a good idea to update the local database of software to make sure you’ve got access to the latest revisions.

Therefore, open a terminal window and type:

```sudo apt-get update```

Allow the operation to complete.

### Step 2: Uninstall Old Versions of Docker
Next, it’s recommended to uninstall any old Docker software before proceeding.

**Use the command:**
```sudo apt-get remove docker docker-engine docker.io```

### Step 3: Install Docker
To install Docker on Ubuntu, in the terminal window enter the command:

```sudo apt install docker.io```


### Step 4: Start and Automate Docker
The Docker service needs to be setup to run at startup. To do so, type in each command followed by enter:

```
sudo systemctl start docker
sudo systemctl enable docker

```

## Install Docker compose on Ubuntu

```
sudo curl -L https://github.com/docker/compose/releases/download/1.18.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose

```
** Check output using below command **
```docker-compose --version```

** output **

```docker-compose version 1.18.0, build 8dd22a9``` 

