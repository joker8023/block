block
================
实现区块链基础功能

Table of Contents
-----------------

  * [Requirements](#requirements)
  * [Usage](#usage)

Requirements
------------

requires the following to run:

  * go


Usage
-------

 ```
     cd bin/
     # 查看命令提示
     ./block
     # 创建钱包地址
     ./block createwallet
     # 查看所有钱包地址
     ./block listaddresses
     # 查看钱包余额
     ./block getbalance --address {钱包地址}
     # 挖矿
     ./block createblockchain --address {钱包地址}
     # 查看所有区块
     ./block printchain
     # 转账
     ./block send -from {钱包地址} -to {钱包地址} -amount {数量}
 ```

 Build
 ------

 ```
    cd src/
    go build -o ../bin/block
 ```
