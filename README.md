# <h2 align=center>Cysic Prover Nodes Testnet III</h2>
------------------------------------------------------------------
- Buy VPS : [t.me/skuycloud](t.me/skuycloud)
- Trakteer buy Coffee : https://trakteer.id/brrrskuy/tip `<---`
------------------------------------------------------------------

Requirement Hardware : 
| Req   | ETH Proof     | Scroll        |
|-------|---------------|---------------|
| CPU   | 8 Core        | 32 Core       |
| RAM   | 32 GB         | 256 GB        |
| GPU   | 24GB VRAM     | 24GB VRAM     |
| DISK  | 30 GB         | 30 GB         |

## >>Register Cysic Nodes
- Regist here : [https://cysic.xyz/zk](https://cysic.xyz/zk)
- Use code : `61264`

## 1. First if you Running in 16GB/8Core Overcommit your New VPS

➡️Here : [Start Overcommit RAM and CPU](https://github.com/Brrrskuy/Overcommit-Extreme-RAM.CPU)

## 2. Install Prover
🛠️ETH Proof Only
  ```
  curl -L https://github.com/cysic-labs/cysic-phase3/releases/download/v1.0.0/setup_prover_only_ethProof.sh > ~/setup_prover.sh && bash ~/setup_prover.sh 0x-Fill-in-your-reward-address-here Your_RPC_URL
  ```
🌐Scroll Proof Only
  ```
  curl -L https://github.com/cysic-labs/cysic-phase3/releases/download/v1.0.0/setup_prover_only_scroll.sh > ~/setup_prover.sh && bash ~/setup_prover.sh 0x-Fill-in-your-reward-address-here Your_RPC_URL
  ```

Please make sure, Change `0x-Fill-in-your-reward-address-here` to your Address Connected in Cysic EVM Keplr and Change `Your_RPC_URL` in Alchemy RPC Endpoint Ethereum Mainnet

## 3. Running Your Prover Nodes
  Create Screen , if `Prover Nodes Successfull` running Detached screen `CTRL+A+D`
  ```
  screen -S cysic
  ```
🗣Start Your Prover Nodes `(same for both)`
  ```
  cd ~/cysic-prover/ && bash start.sh
  ```
  if see screen 
  ```
  screen -r cysic
  ```
  
------------------------------------------------------------------
## Join Telegram Channel 
For Updates, Questions and other Guides Join the Community :

[Skuy Vibes Cloud](https://t.me/skuycloud) or [Airdrop Family IDN](https://t.me/AirdropFamilyIDN)
