**【功能简介】**

_子链协议合约定义了用于上层的共识协议。子链的共识协议可以分为多种_

1. 处理类共识协议（类似于CPU），比如POS，POW，PBFT等
1. 文件存储类共识协议（类似于硬盘），比如POF（IPFS）,FileCoin等
1. 功能类共识协议，比如随机数，时戳等
1. 自定义类共识协议，比如投票，IOT，sensor network等

_子链协议合约部署之后，可以让具有对应模块的SCS注册，并缴纳保证金。在等待时间之后（通常是50个block），就成为子链的候选SCS节点。_

_子链协议合约必须与对应的SCS模块协同工作。墨客提供一个POS的实现，包括SubchainProtocolBase.sol 和相应的SCS模块。_

**【功能模块】**

* 1.SCSList，存储所有注册并缴纳保证金的节点
* 2.bondMin，参与这个协议所需最低保证金
* 3.register（注册）：具有相应模块的SCS调用注册，并缴纳保证金
* 4.withdraw(退出)：SCS可以选择退出，并在一定时间后返回保证金
* 5.getSelectionTarget：根据子链要求的SCS数得到选择标准，即如何从总数中随机取出需要的SCS节点数
* 6.approveBond（子链押金授权）：授权SCS参与的子链可以在SCS表现恶意的时候没收保证金
* 7.forfeitBond（没收押金）：子链没收SCS的押金