# RaspberryPi-VPN

Setup a RaspberryPi to work as a VPN


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


## Instructions
1. 