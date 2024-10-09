# Nexus-Prover

## Method 1. Web Browser
Contribute to Nexus zkVM Prover by click Connect button: https://beta.nexus.xyz/

![image](https://github.com/user-attachments/assets/ec13a340-9c54-4419-a1fe-e3ad0855b9dd)


## Method 2. Linux Server
1. Install Dependecies
```console
sudo apt update && sudo apt upgrade -y
```
```console
# Install packages
sudo apt install curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev  -y

# Install Rust
curl https://sh.rustup.rs -sSf | sh
source $HOME/.cargo/env
export PATH="$HOME/.cargo/bin:$PATH"

rustup update

rustc --version
```

2. Run Prover

*Open screen*
```console
screen -S nexus
```
*Run:*
```console
curl https://cli.nexus.xyz/install.sh | sh
```
![image](https://github.com/user-attachments/assets/6d79fad5-4153-4927-b3e2-559fe70fe5b5)

To minimize screen: `CTRL+A+D`

To retun screen: `screen -r nexus`


## Track your Contribution
***There is no wallet or social connection yet but team is tracking your computer Contributions and will add a leaderboard later***

![image](https://github.com/user-attachments/assets/9f8f86bd-a250-4b9e-834c-170a3f66f371)

![image](https://github.com/user-attachments/assets/ad0ed68a-d777-408f-94c2-9e294c8163d9)

![image](https://github.com/user-attachments/assets/9f539bb8-083f-4723-8c1a-24e09189ebc9)



