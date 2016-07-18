Ubuntu Setup
============

Install Nvm + NodeJs
--------------------

```
sudo apt-get install build-essential libssl-dev
curl https://raw.githubusercontent.com/creationix/nvm/v0.25.0/install.sh | bash
```

关掉terminal，重新打开才能使用`nvm`命令

```
nvm install 6
nvm use 6
```

然后使用：

```
node -v
```

确定输出的版本号为`6.x`