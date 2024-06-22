
####  Farcaster WarpCast Node Kurulumu
![image](https://raw.githubusercontent.com/farcasterxyz/.github/master/farcaster.jpg)


 * [Twitter](https://twitter.com/suatayaz79)
 * [Warpcast](https://warpcast.com/suatayaz)
 * [Warpcast üyelik  link ](https://warpcast.com/~/invite-page/327600?id=afed1bfc)
 *  Node Kurulumu için WarpCasty üyelik ihtiyacınız olacaktır.. Destek için Yukarı ref linkten üyelik yapabilirsiniz.
 
 
 * Node  Anasayfa   https://www.thehubble.xyz/intro/hubble.html


16 GB of RAM
4 CPU cores or vCPUs
140 GB of free storage




## ...Ubuntu  Güncelleme...

```shell
sudo apt update -y
```

```shell
sudo apt upgrade -y
```

```shell
sudo apt install screen -y
```

```shell
Screen -S  Farcaster
```


## ..Docker Kurulum ..	

```shell
sudo apt-get update
sudo apt-get install \
    ca-certificates \
    curl \
    gnupg \
    lsb-release
```

```shell
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg

echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
```


```shell
sudo apt-get update
```

```shell
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
```

```shell
sudo systemctl start docker
sudo systemctl enable docker
```

```shell
sudo curl -L "https://github.com/docker/compose/releases/download/v2.20.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```

```shell
sudo chmod +x /usr/local/bin/docker-compose
```
 
## .. Kurulum Kod ...
 
```shell
curl -sSL https://download.thehubble.xyz/bootstrap.sh | bash
```

- Sizden sırasıyla ETH , OP mainnet  RPC soracak    RPC leri  bu sitelerden ayarlayacağız..  https://app.infura.io/dashboard ve https://www.alchemy.com/

#### 1-ETH mainnet RPC link
#### 2-Op Mainnet RPC link
#### 3-Warpcast FID numaranızı girin 

Profiliniz sağ üstten 3 çizgi  about...



- Aşağıdaki gibi çıktı  görmelisiniz.. Uzun sürebilir..

![image](https://github.com/Sazy67/Farcaster_Node/blob/main/war.png)


- Son olarak   http://SUNUCU-IP:3000 şeklinde  kontrol edebilirsiniz.

![image](https://github.com/Sazy67/Farcaster_Node/blob/main/www.png)
