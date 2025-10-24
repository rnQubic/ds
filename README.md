### 个人喜欢玩黑箱文化，你们不一样，别上头。

### 配置文件建在策略根目录

### 文件名字.env


## 单向持仓 模式


# 内容


###  DEEPSEEK_API_KEY= 你的deepseek  api密钥

###  BINANCE_API_KEY=

###  BINANCE_SECRET=

###  OKX_API_KEY=

###  OKX_SECRET=

### OKX_PASSWORD=

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

```
conda activate ds
```

```
pip install -r requirements.txt
```

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
