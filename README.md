# Essays

本`repo`记录了我在2022年写的一些用$\LaTeX$写的文章（大多数是实验报告）

发布出来仅仅是出于分享的目的（当然如果你发现错误了欢迎指正），
**禁止抄袭、复制、编造实验数据**。

`repo`中可能文章里存在$\LaTeX$排版上的问题，欢迎提出宝贵的意见。

## Links

* [2022-03-22 光电效应实验](./0f7b67)
* [2022-03-18 自由落体测重力加速度](./70be0b)
* [2022-03-15 单摆法测重力加速度](./4ed5e0)

## Change Log

### 2022/3/31 更新

更新了文件目录的更新规则（~~万一明年还要继续写呢……~~）

### 2022/3/27 更新

[2022-03-22 光电效应实验](./0f7b67)（大雾A标准，包含补偿法实验内容）

感谢@hkxa0933 的帮助，阿里嘎多。

 > 这个实验应该是2022/3/21做的，然后第二天开始动笔，于是目录就很随意地用了`0322`这个名字……
 >
 > 做这个实验的时候，给一点小建议：带个**支架，拿手机把实验数据录下来**（不是大雾A的话可能不需要），补偿法最后有大概500个数据点……自动的话，每个数据就只有1s的时间记录；为了速度的话，建议现场能记多少是多少，没记录完整地回来看回放。
 >
 > > 或者学我用GoPro也行……（草）

做实验其实没什么需要特别注意的（不过有的时候需要考虑一下是不是自己实验仪器有问题，因为真的可能有问题，发现不对劲的时候及时举手提问……老师在旁边会帮你的）

处理实验数据的时候简单地线性回归就行，不用自己写代码。

> 这次我把用的`jupyter notebook` 贴出来了，前两个代码不想找了……也没什么特别难的

在一些特殊的地方可以先用$\log$处理一下，再回归分析。

[2022-03-18 自由落体测重力加速度](./70be0b)

[2022-03-15 单摆法测重力加速度](./4ed5e0)

感谢@Thomas Hu的帮助（~~关于我什么准备都没做然后空手去一教是否做错了什么事情~~）

> 实验时间：2022/3/14，不过报告写起来稍微麻烦一点（主要是刚开始使用$\LaTeX$排版……熟悉一点就好了）
>
> > $\LaTeX$排版并不是必须；如果你实验报告肝不完了可以用Word套用一下模板；不过为了工整最好还是用$\LaTeX$排一下吧……看起来会更整洁一点。  
>
> 这个实验里要求不确定度分析……所以尽量多测几次摆长（不要事后编数，隔一段时间多测几次，不会累死人的……）

稍微注意一下：光电门测量重力加速度的时候，由于电磁铁上面有剩磁（延时下落），所以$t_1,t_2$这两个数据都不能用；必须用$t_2-t_1$来处理。

数据处理和绘图拿Python就够了……而且默认的参数基本不用调（如果你没时间的话）

不过没整理代码……下次一定，这次就算了吧（小声）
