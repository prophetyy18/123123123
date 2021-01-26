# BSCIDE新年活动
## 活动介绍

本次活动是ChainIDE与Binance联合举办的新年体验活动，我们希望大家能从本次活动当中**收获到知识**，同时获取一些收益。

本次活动将通过2个部分进行，我们会提供一份使用ChainIDE部署和编译以及交互的教程，大家跟随教程做一遍，然后将自己在教程最后反馈的截图和钱包地址反馈到我们的微信群或telegram群当中，就可以获取0.1个BNB的奖励。

微信群

telegram群

https://t.me/joinchat/GKXPkbNCoKLCxixP

## 流程介绍

ChainIDE是世界上最大的在线编译平台之一，它可以支持多链的在线编译、链上部署、合约交互等功能。Chainide支持的环境包括Facebook Diem, Etherum, AntFinancial OpenChain, FiscoBcos, Hyperledger Fabric等共计10条不同的公链和联盟链。现已经被超过120个国家的开发者所使用，同时编译的合约超过350万份。

本次活动是希望各位开发者和爱好者能尝试使用ChainIDE进行操作，了解如何在区块链上进行Metamask钱包节点设置、合约编译部署以及交互等功能。

让我们一起开始吧~

首先我们可以通过这篇文章完成关于Metamask设置BSC RPC网络，这样我们就可以使用Metamask与Bsc网络进行交互了。

（附文章链接）

![](https://github.com/prophetyy18/BSCIDE-/blob/master/picture/Spring%E6%B4%BB%E5%8A%A8%E5%9B%BE1.png)

在完成了Metamask设置之后，我们可以回到bscide.com的主界面，点击右上角的目录栏，然后点击create project创建一个新的项目。

![](https://github.com/prophetyy18/BSCIDE-/blob/master/picture/Spring%E6%B4%BB%E5%8A%A8%E5%9B%BE2.png)

点击进去后，可以进入到项目当中，点击Storage.sol文件，这是ChainIDE为大家准备的一个非常简单的存证合约，我们在它的基础上进行一些修改，加入红色区域内的代码部分。

```
    function getAddress() public view returns(address) {
        return msg.sender;
    }
```
 
![](https://github.com/prophetyy18/BSCIDE-/blob/master/picture/Spring%E6%B4%BB%E5%8A%A8%E5%9B%BE3.png)

然后点击右侧的Compile Storage.sol进行solidity文件的编译，编译成功后会出现下面ABI和bytecode的内容，同时在控制台上会输出Compile contract success。

![](https://github.com/prophetyy18/BSCIDE-/blob/master/picture/Spring%E6%B4%BB%E5%8A%A8%E5%9B%BE4.png)

此时通过点击右侧的Deployment & Interaction进入到部署页面，设置好gas limit(1000000)和gas fee(20)，然后点击Deploy同时在Metamask上确认。

![](https://github.com/prophetyy18/BSCIDE-/blob/master/picture/Spring%E6%B4%BB%E5%8A%A8%E5%9B%BE5.png)

最后，我们要与部署在链上的合约进行一个交互，获取我们自己的钱包地址。
点击interact-Storage-getAddress打开，然后点击commit与合约进行交互。

![](https://github.com/prophetyy18/BSCIDE-/blob/master/picture/Spring%E6%B4%BB%E5%8A%A8%E5%9B%BE6.png)

在交互完成后，大家根据这个截图，就可以在微信群或者telegram群当中获取奖励啦，我们在活动结束之后会进行统计和发放，感谢大家的参与。

![](https://github.com/prophetyy18/BSCIDE-/blob/master/picture/Spring%E6%B4%BB%E5%8A%A8%E5%9B%BE7.png)

请大家在提交的时候附上自己交互的这张截图，以及获取奖励的钱包地址，谢谢合作~
