# RaspberryPi-VPN

Setup a RaspberryPi to work as a VPN
[https://pivpn.io/](https://pivpn.io/)


## Requirements
1. Upgrade `pip`
    ```
    python3 -m install --upgrade pip
    ```
1. Install `ansible`
    ```
    python3 -m install --user ansible
    ```


### macOS Specific
1. Add Python imported console scripts to your path
    ```
    echo "export PATH=\$PATH:~/Library/Python/3.8/bin" >> ~/.zshenv
    ```
1. Install [homebrew](https://brew.sh/)
1. Install `sshpass`
    ```
    brew install esolitos/ipa/sshpass
    ```


## Initial Setup
1. Install Raspberry Pi OS Lite
1. Connect Raspberry Pi to ethernet cable, monitor, keyboard, and mouse
1. Log into Raspberry Pi using default username `pi` and password `raspberry`
1. Run these commands to enable and start `ssh`
    ```
    sudo sytemctl enable ssh
    sudo systemctl start ssh
    ```
1. Now you can logout and disconnect the monitor, keyboard, and mouse - everything else will be done remotely


## VPN Setup
1. 