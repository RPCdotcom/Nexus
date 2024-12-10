
![1500x500](https://github.com/user-attachments/assets/7cf9996a-5dcb-49e3-8f2e-07d2940fd580)

## Nexus Labs Node Kurulum : 

#### Sunucu Özellikleri : 

- 4 CPU 
- 6 RAM
- Ubuntu 22.04

```bash
sudo apt update && sudo apt upgrade
```
```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev protobuf-compiler libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen unzip lz4 -y
```

#### Screen : 

```bash
screen -S nexus
```

#### Çalıştıralım  : 

```bash
curl https://cli.nexus.xyz/ | sh
```

![image](https://github.com/user-attachments/assets/d5da2401-e8b0-4810-8679-5af43878a986)


- Y yazıp enterliyoruz.

![image](https://github.com/user-attachments/assets/83bd5487-0db1-45d9-9540-9ca91f1d484e)

- İşlemlerin bitmesini bekliyoruz.


![image](https://github.com/user-attachments/assets/1b2c8c1f-dbc9-4643-bdf2-bd0d337ea130)

CTRL C ile durdurun.

##### YOUR_PROVER_ID Kısmına kendi id'nizi yapıştırın.

```bash
echo "YOUR_PROVER_ID" > ~/.nexus/prover-id
```

####### Prover İD : 

![image](https://github.com/user-attachments/assets/937c9f53-bb8e-442b-bd24-5df747173e39)
