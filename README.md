# chainmaker_note

### 搭建区块链环境

https://docs.chainmaker.org.cn/v2.3.6/html/quickstart/%E9%80%9A%E8%BF%87%E5%91%BD%E4%BB%A4%E8%A1%8C%E4%BD%93%E9%AA%8C%E9%93%BE.html


### Remix IDE 简介

安装命令：
```
npm install -g @remix-project/remixd
```

本地运行命令：
```
remixd -s D:\workspace_remix\ --remix-ide https://remix.ethereum.org/
```

### 用 solcjs 编译

安装命令：
```
npm install solc -g
```

编译命令：
```
solcjs MyContract.sol  --optimize --abi --bin
```
一次性编译多个文件：
```
solcjs --bin --abi --include-path D:\workspace_remix\test\*.sol -o D:\workspace_remix\test\out
```

