数字币交易策略代码
捕捉插针行情策略程序，在市价下方以固定价差挂买单限价单，比如市价是1000，我们就挂700，当市价变为1100，我们先取消上一个挂单，然后挂800，不断重复这个动作，直到出现插针行情。
![avatar](https://github.com/ninki51/btcTrade/blob/main/%E6%B4%BC%E5%9C%B0%E7%AD%96%E7%95%A51_1.png)
当我们的挂单被交易后，我们迅速在能盈利的时刻卖出，实现获利。
![avatar](https://github.com/ninki51/btcTrade/blob/main/trade2.png)
整个过程完成有程序控制，能迅速捕捉插针行情，迅速卖出
![avatar](https://github.com/ninki51/btcTrade/blob/main/%E6%B4%BC%E5%9C%B0%E7%AD%96%E7%95%A5%E4%BB%A3%E7%A0%81.png)
程序使用Go语言编写，需要的朋友联系微信 jianke9982

视频演示网址 https://youtu.be/PRcFrPP6qjI
