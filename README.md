# Pet Shop Truffle Box

This box has all you need to get started with our [Pet Shop tutorial](http://truffleframework.com/tutorials/pet-shop).

## Installation

1. 安装truffle node.js   [Ganache](http://truffleframework.com/ganache/)
    ```javascript
    npm install -g truffle
    ```

2. 在根目录voting 编译
    ```javascript
    truffle compile
    ```

3. 打开Ganache 部署 
    ```javascript
    truffle migrate
    ```

4. Run the `liteserver` development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.
    ```javascript
    npm run dev
    ```

5. 安装浏览器插件METAMASK 
    MetaMask 是一款插件形式的以太坊轻客户端，开发过程中使用MetaMask和我们的dapp进行交互是个很好的选择，通过此[链接](https://metamask.io/)安装，安装完成后，浏览器工具条会显示一个小狐狸图标。

6. 这里我们通过还原一个Ganache为我们创建好的钱包，作为我们的开发测试钱包。点击页面的 **Import Existing DEN**，输入Ganache显示的助记词。自己设置密码。

    连接开发区块链网络。默认连接的是以太坊主网（左上角显示），选择**Custom RPC**，添加一个网络：**http://127.0.0.1:7545**，点返回后，显示如下：![](https://learnblockchain.cn/images/metamask-account1.png)

