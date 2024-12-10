
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

#### Sunucunuzda Cargo Yoksa : 
```bash
sudo curl https://sh.rustup.rs -sSf | sh
```
Soru Soracaktır normal indirme vb. 1 yazıp enterleyin.
```bash
source $HOME/.cargo/env
```
```bash
export PATH="$HOME/.cargo/bin:$PATH"
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

![image](https://github.com/user-attachments/assets/db365227-94d4-41a9-8274-72c9cd70a456)


### CTRL C ile durdurun.

### YOUR_PROVER_ID Kısmına kendi id'nizi yapıştırın.

```bash
echo "YOUR_PROVER_ID" > ~/.nexus/prover-id
```

##### Prover ID : 

![image](https://github.com/user-attachments/assets/c357d79c-3339-47f3-83f9-70f36c7df49f)

- Kopyala butonuna tıklayın size daha uzun bir id vericek bu sunucudaki cli için . 

![image](https://github.com/user-attachments/assets/10f6d4c5-a4c9-40bc-8f36-10466ec64140)
![image](https://github.com/user-attachments/assets/88b4e662-9241-4e7c-bd5d-611ac1524cdc)

##### Sonrasında komutu yapıştırın ; 


![image](https://github.com/user-attachments/assets/baf7030c-c33d-44c4-b331-1b367abbcfed)

#### Yeniden Çalıştıralım  : 

```bash
curl https://cli.nexus.xyz/ | sh
```

![image](https://github.com/user-attachments/assets/a057b271-1c1c-4fcf-bd2f-756ea1e955e2)

##### Artık doğru ID ile çalışmaya başlayacaktır. 
##### CTRL A + D ile screenden çıkabilirsiniz - kendisi çalışmaya devam edecektir.
