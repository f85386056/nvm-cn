## 安装

`wget -qO- https://raw.githubusercontent.com/chaos-zhu/nvm-cn/master/install.sh | bash`

or

` bash -c "$(curl -fsSL https://raw.githubusercontent.com/chaos-zhu/nvm-cn/master/install.sh)" `

## 卸载

` bash -c "$(curl -fsSL https://raw.githubusercontent.com/chaos-zhu/nvm-cn/master/install.sh)" `


## 使用

```bash
nvm ls

# 列出所有可安装版本
nvm ls-remote

# 安装某个版本Node
nvm install lts
nvm install v12.20.1
nvm install v15.5.1

# 切换Node版本
nvm use system
nvm use 14.15    # 不用全部打出版本号

# 更新nvm
nvm-update
```

## npm 换源
```bash
# 查看配置
npm config ls

npm config set registry https://registry.npm.taobao.org 
```
