# DouZeroBid_For_HLDDZ_H5: 一个未完成的关于DouZero叫牌版的测试

*   本项目基于[DouZeroBid](https://douzero.org/bid/)
*   游戏环境是欢乐斗地主h5版(https://hlddz.huanle.qq.com),需要使用Fiddler或其他工具替换https://hlddz.huanle.qq.com/src/version/hlddz-1.5.3.0.build0.js
*   在浏览器console里搜索 记牌器 就可以看到实时叫牌出牌胜率

## 说明
*   边逆向边写js水平也一般，所以代码质量很差
*   wss协议那面看着头疼，所以自动出牌功能没写，有能力的可以自己完成
*   **本项目仅供学习以及技术交流，请勿用于其它目的，否则后果自负。**


## 潜在Bug
*  因为直接调用的在线版，所以偶尔会碰到player_id = 0,叫牌胜率无法获取的情况，有能力的可以自行处理

## 鸣谢
*   [DouZero](https://github.com/kwai/DouZero)

