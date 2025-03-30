# chainmaker_note

### Remix IDE 简介

安装命令：
```
npm install -g @remix-project/remixd
```

本地运行命令：
```
remixd -s D:\workspace_remix\ --remix-ide http://remix.ethereum.org/
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

