# Legacy Project

GO TO [https://github.com/Dynamicer/NuCypher-Helper](https://github.com/Dynamicer/NuCypher-Helper)

# NuStart
This is a pure translation for [https://github.com/Achi101/NuStart](https://github.com/Achi101/NuStart) .

NuCypher node installation automation

Before running the script, prepare the Keystore file for the worker wallet and Endpoint info

NuCypher 节点安装一键包（适用 Ubuntu）

使用一键包前，请准备好 worker 钱包的 Keystore 文件和 infura Endpoint 信息

你可能需要先注册 [infura](https://infura.io/) ，建立项目，在 Endpoint 信息中复制 WSS 开头的链接

Add a user to the system:

```bash
adduser 'USER' -ingroup sudo && su 'USER'
```

Download and run the Script & Enter the required values:
```bash
cd && wget https://raw.githubusercontent.com/Dynamicer/NuStart/master/nu-start && chmod u+x ~/nu-start && ./nu-start
```
