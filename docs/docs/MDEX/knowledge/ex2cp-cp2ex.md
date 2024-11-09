# MDEX与MDCP互通的一些小方法

最近EX与CP的谱师重合度越来越高，同时也有越来越多的小伙伴愿意尝试Muse Dash Extra Editor，但是在操作上会有一些不便；

所以这次的话呢给各位带来一些EX与CP互通的小技巧

<strong>注：本次教程所用到的软件均不给予下载地址，还请自行寻找喵</strong>

## 如何从MDEX格式转变为MDCP格式

<em>为了方便后续称呼将会仅称呼双方软件所用的格式</em>

1. 首先的话呢我们需要用到一个软件【BMS2CP】，当我们得到它后双击打开会看到下面这个界面：

![image-ex2cp1](img\ex2cp-cp2ex.assets\image-ex2cp1.png)


2. 然后我们将要转的“bms”文件拖进到这个界面中，拖进去后会显示你的bms目录位置，如下图：

![image-ex2cp2](img\ex2cp-cp2ex.assets\image-ex2cp2.png)

3. 最后的话呢我们按下键盘上的【ENTER】键即可转变成功啦，转变成功后会在相同目录下出现一个【xxx_out.mdcpmf】,如下图：

![image-ex2cp3](img\ex2cp-cp2ex.assets\image-ex2cp3.png)

<strong>记得将文件名修改为【score.mdcpmf】，否则MDCE将不会读取并报错。</strong>

### 然后呢会有一些特殊情况需要注意，可以认为是bug。（但实际上就是不想继续看对应了）

- 本工具专门用于"BMS"谱面转化为"mdcpmf"文件,只支持基础Note。

本工具暂不支持 MD + EX 的所有特效,所有特效请到CT中自行手抄。

不过还是支持如：场景切换、变速等特效。

- 在转换后会有一定的note缺失，如音符、齿轮等，还请转换后认真检查一下

- 本工具转换出来的mdcpmf文件的谱面长度默认为0,转换完成后请自行用MDCT加载后调整谱面长度时间。
<em>因需遵守Muse Dash CustomPaly对于制谱器的各项条款，故具体位置还请自行寻找，本人恕不告知。</em>

- 如果还有其他bug欢迎发送评论提醒我补充谢谢，以及你得到这个软件后请勿随意外传，不过也要想想为什么会有这个软件的出现）

## 如何从MDCP格式转变为MDEX格式