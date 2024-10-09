# Nexus-Prover

## Method 1. Web Browser
Contribute to Nexus zkVM Prover by click Connect button: https://beta.nexus.xyz/

![image](https://github.com/user-attachments/assets/ec13a340-9c54-4419-a1fe-e3ad0855b9dd)


## Method 2. Linux Server
**1. Install Dependecies**
```console
sudo apt update && sudo apt upgrade -y
```
```console
# Install packages
sudo apt install curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev  -y
```
```console
# Install Rust
sudo curl https://sh.rustup.rs -sSf | sh
```
```console
# Add Rust to path
source $HOME/.cargo/env
export PATH="$HOME/.cargo/bin:$PATH"
```
```console
rustup update

rustc --version
```

**2. Run Prover**

*Open screen*
```console
screen -S nexus
```
*Run:*
```console
sudo curl https://cli.nexus.xyz/install.sh | sh
```
![image](https://github.com/user-attachments/assets/6d79fad5-4153-4927-b3e2-559fe70fe5b5)

To minimize screen: `CTRL+A+D`

To retun screen: `screen -r nexus`

**3. Save Prover ID file**

You'll get a `prover-id` file in `/root/.nexus/` representing your unique contribution ID to Prover Node

![Screenshot_3](https://github.com/user-attachments/assets/5362c2b7-f116-4086-aeec-44fc7b425d05)


## Track your Contribution
***There is no wallet or social connection yet but team is tracking your computer Contributions and will add a leaderboard later***

![image](https://github.com/user-attachments/assets/9f8f86bd-a250-4b9e-834c-170a3f66f371)

![image](https://github.com/user-attachments/assets/6bf910e5-a9e0-443e-951a-bf828818fbfc)




