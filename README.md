# Install-vagrant

### How to setup Vagrant on Ubuntu 22.04 using apt
You can quickly achieve the installation of Vagrant on Ubuntu in a pretty straightforward way by following the given steps:

##### Step 1: Update Ubuntu packages

First things first, update the system repo to the latest versions. To do this, open your terminal by hitting the “CTRL+ALT+T” shortcut keys together and issue the following update command:

```sudo apt update```


##### Step 2: Upgrade Ubuntu packages

Once you run the update command, you will be alerted of the number of packages that require an upgrade at the end of the update command. This tells you that the mentioned number of packages have released newer versions. To upgrade them, run the following command, and remember that you can skip this step once you find out that all of your packages are up to date:

```sudo apt upgrade```

##### Step 3: Install VirtualBox

Next up, we will install VirtualBox on our system using the following command:

```sudo apt install virtualbox```

##### Step 4: Install Vagrant

After you are done installing VirtualBox, it is time to download the Vagrant deb package by running the following command on your terminal:

```wget https://releases.hashicorp.com/vagrant/2.2.19/vagrant_2.2.19_x86_64.deb```

Subsequently, use the following command to install the deb package from the apt installer:

```sudo apt install ./vagrant_2.2.19_x86_64.deb```

##### Step 5: Verify Vagrant installation

Here, we will run the check version command to ascertain whether or not we successfully installed Vagrant on our Ubuntu system.

```vagrant --version```
