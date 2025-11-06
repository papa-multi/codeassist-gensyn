

<img width="1536" height="1024" alt="codeassist1" src="https://github.com/user-attachments/assets/e85a553e-c9e6-4b98-9752-098228cbb1f4" />


# 1) Install Dependencies :

```
 sudo apt update && sudo apt upgrade -y
```

```
sudo apt install screen curl iptables build-essential git wget lz4 jq make gcc nano automake autoconf tmux htop nvme-cli libgbm1 pkg-config libssl-dev libleveldb-dev tar clang bsdmainutils ncdu unzip libleveldb-dev  -y
```

```
sudo apt install python3 python3-pip python3-venv python3-dev -y
```
```
sudo apt update
curl -fsSL https://deb.nodesource.com/setup_22.x | sudo bash -
sudo apt install -y nodejs
node -v
npm install -g yarn
yarn -v
```


```
curl -o- -L https://yarnpkg.com/install.sh | bash
```

```
export PATH="$HOME/.yarn/bin:$HOME/.config/yarn/global/node_modules/.bin:$PATH"
```

```
source ~/.bashrc
```


### Linux (or alternate MacOS install, for those without Brew)

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```
```
source $HOME/.local/bin/env
```


next step install docker [docker](https://github.com/0xmoei/Linux_Node_Guide/blob/main/linux-config.md#docker-docker-compose)


--------------------------------------
#2) Downloading the Code

To download the code, simply clone the repository:

```bash
git clone https://github.com/gensyn-ai/codeassist.git
cd codeassist
```

run

```
uv run run.py
```

# If you run it on a VPS you need to run SSH from your local PC

```
ssh -N -L 3000:localhost:3000 -L 8000:localhost:8000 -L 8008:localhost:8008 root@ipvps
```

After solving the problem, go back to the terminal, press Ctrl+C, and wait for it to finish pushing the data


<img width="1280" height="554" alt="image" src="https://github.com/user-attachments/assets/3091563c-4a77-4ce6-b95d-41189f2e1da5" />



