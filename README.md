# my-desktop-ansible
Here you can find a piece of code used for my desk provisioning.
Most of this ansible code was customized to my own purposes and works on fedora 26

## Installation steps

* ``` git clone git@github.com:kaarolch/my-desktop-ansible.git ```
* ``` cd my-desktop-ansible ```
* ``` chmod +x ./bootstrap.sh ```
* ``` ./bootstrap.sh ```
* ``` ansible-playbook main.yml  -K ```

The -K option ask about sudo password

## Tags support
Sometimes I need to run only specific role or group of roles. Now the tags are in place each role owns tag equal role name.

Example run:

``` ansible-playbook main.yml  -K --tags atom```

## TO DO
* Add missing configuration files and plugins for some packages
* Add gnome customization
* Add more tags
