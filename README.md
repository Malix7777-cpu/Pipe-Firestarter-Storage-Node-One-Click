<div align="left">

#  **Pipe Firestarter📔**

⚡ Decentralized storage & delivery network
🔒 Secure | Fast | Censorship-resistant
💰 Powered by $PIPE tokens (1 PIPE ≈ 1GB)
🌍 Built on Solana → Already storing 1PB+ data

🚀 Future of Storage + CDN + Edge Compute

</div>

---

# Pre-Requirements 🛠

## Install All Require Dependecies


```
sudo apt update && sudo apt upgrade -y
```

```
sudo apt install curl iptables build-essential git wget lz4 jq make gcc postgresql-client nano automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev tar clang bsdmainutils ncdu unzip libleveldb-dev libclang-dev ninja-build -y
```

## Install rustup

* For {Linux}

```
curl https://sh.rustup.rs -sSf | sh
```

```
source $HOME/.cargo/env
```

* For {Mac}

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

```
source $HOME/.cargo/env
```

Check version

```
rustc --version
cargo --version
```

---

# Installation

### Clone the Repo


```
git clone https://github.com/PipeNetwork/pipe.git
cd pipe
```

### Install pipe-cli

```
cargo install --path .
```

### Verify The Installation

```
pipe -h
```

### Set-Up a User

```
pipe new-user <your_username>
```

>Replace <your_username> with your:

>Save `Solana Pubkey:` 

### Set-Up Your Password

```
pipe set-password
```

>Enter a Strong PASS:


### Save Your `Credentials`

>Open the file and save all the credentials in it:

```
nano ~/.pipe-cli.json
```

---

## Basic CLI's Operations

### Referral Campaign

>You'll earn up to 100 PIPE for every referral who swap at least 1 SOL DEVNET for PIPE


#### Enter the Refer Code:

```
pipe referral apply MALIX777-MNBF
```

#### Get Your referral code:

```
pipe referral generate
```

#### Check your referral stats

```
pipe referral show
```

---

### Swap Sol (Devnet) to Pipe

* Get Sol Devnet Faucet from [here](https://faucet.solana.com/)

* Swap

```
pipe  swap-sol-for-pipe <AMOUNT_SOL>
```

>Swap minimum 1sol to pipe

---


### Upload a File

```
pipe upload-file <FILE_PATH> <FILE_NAME>
```

* >Replace <FILE_PATH> & <FILE_NAME> with their actual: 

* >Dont upload any `confidential` file (Wallet keys & personal docs)

* >You can upload any videos or large file too:

* >For home path, use: 

```
~/Name_of_your_file
```

### Create Public Link

>We will create the public link of our uploaded file: 

```
pipe create-public-link <FILE_NAME>
```

* >Replace <FILE_NAME> which you have used earlier while uploading a file:


### Check Token-Usage

>You can get to know about the usage of the pipe devnet tokens, after uploading and Downloading Files:
```
pipe token-usage
```


### Many CLI's Operations are there in pipe, So you can read and apply from pipe's official Repo: [Pipe_Repo](https://github.com/PipeNetwork/pipe)

---

## 🎯 How to Earn the 🔥Firestarter Role

### 1. Share Your Contribution Proof
- **Upload your video(s)**
- **Take a screenshot** of your uploaded file info (showing the public link).
- **Post the screenshot and public link** in the `#firestarter-storage-share` channel on Discord.
- The team will **verify** and grant you the role!

### 2. Make a Good Tweet
- **Post your screenshot and public file link** on Twitter with positive feedback about the project.
- **Share your tweet link** in the `#pipe-community-social` channel on Discord.
- The team will **verify** and grant you the role!

**👉 [Join the Discord server](https://discord.gg/bEJ3YCHm) to get started!**

---


## 🤖 Need Help

 📺 **Guides & Updates:** [@LEGENDARYLOOTERSSS](https://t.me/LEGENDARYLOOTERSSS)

😁 Thanks a lot! 👻 Keep building, keep coding & keep shining 💗🔥☠

</pre>
