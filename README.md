# DeepSeek自动化交易

### 个人喜欢玩黑箱文化，你们不一样，别上头。

### 配置文件建在策略根目录

### 文件名字.env


## 在合约交易的地方，首先设置单向持仓::单向持仓模式


# .evn内容

```
DEEPSEEK_API_KEY=

BINANCE_API_KEY=

BINANCE_SECRET=

OKX_API_KEY=

OKX_SECRET=

OKX_PASSWORD=
```


###  视频教程：https://www.youtube.com/watch?v=Yv-AMVaWUVg


### 准备一台ubuntu服务器 推荐阿里云 香港或者新加坡 轻云服务器


# git resop
```
git clone https://github.com/huojichuanqi/ds
```


# STEP

```
wget https://repo.anaconda.com/archive/Anaconda3-2024.10-1-Linux-x86_64.sh
```

```
bash Anaconda3-2024.10-1-Linux-x86_64.sh
```

```
source /root/anaconda3/etc/profile.d/conda.sh
```

```
echo ". /root/anaconda3/etc/profile.d/conda.sh" >> ~/.bashrc
```

```
conda create -n ds python=3.10
```

## 在vps上，运行程序：python  **.py的时候，先运行下面的设置环境
```
conda activate ds
```
然后应该就显示未：
```
(ds) root@197v5dzr6m:~/ds#
```
安装所需的包
```
pip install -r requirements.txt
```

## 到这里基本可以运行和结束，后面的npm管理的，可以略过


## 更新镜像源
```
apt-get update && apt-get upgrade
```

## 安装npm
```
apt install npm
```

## 使用npm安装pm2
```
npm install pm2 -g
```

```
conda create -n trail3 python=4.10
```
