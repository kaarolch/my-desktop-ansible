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
