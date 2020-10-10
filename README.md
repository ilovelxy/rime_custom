# rime_custom

#### 写在前面

基于某种不可抗力的影响，如果本篇文档无法正常显示，可参见[pdf文档](README.pdf)



如果你正在**面临以下问题**，那么该输入法就是你需要的：

1. 很喜欢搜狗输入法的使用体验，却又很反感自带的弹窗（右下角弹窗和广告弹窗）
2. 对自己的打字隐私有所考虑
3. 希望一款输入法能够自由地导入和导出词库
4. 如果我对该输入法的某些地方不满意，能够自己随意修改的话就好了
5. 希望换一种思路思考 编程语言 和“编译原理”

#### 关于rime输入法（小狼毫输入法）

rime输入法是一款优秀的、跨平台、开源、可高度定制、无任何广告、速度快、所有用户数据都储存在本地 的输入法，支持`Windows`,`macOS`,`Linux`,`Android`平台。

自然也会有一些缺点，比如简单自定义和使用比较简单，深度定制的门槛比较高。

本项目简单定制了一款简体中文（繁体中文）输入方案，**注意：不是开发，rime输入法是本来就有的，本文所做的只是在原有输入法的基础上缝缝补补，拼拼凑凑，照猫画虎，依葫芦画瓢DIY的一款个人输入法而已**,引入了50W词库，基本能够满足日常使用。

#### 最简使用教程

1. 去rime官网(https://rime.io)下载自己平台下的安装包并安装。过程如下：

   ![主页](./Screenshots/homepage.png)

   ![](./Screenshots/install_1.png)

   ![](./Screenshots/install_2.png)

   ![](./Screenshots/install_3.png)

   ![](./Screenshots/install_4.png)

   ![](./Screenshots/install_5.png)

2. 将本项目`resources` 文件夹下的4个后缀名是`.yaml`的文件放到程序的“用户文件夹”内。

   **（鉴于国内访问github网站过慢，提供一个百度网盘链接：链接：https://pan.baidu.com/s/1bp3kKyPPCmw5E4An0q-1gw 
   提取码：i0lg 
   复制这段内容后打开百度网盘手机App，操作更方便哦）**

   “程序文件夹”默认是`%AppData%\Roming\Rime`文件夹，（如果安装的时候没有更改任何安装位置设定），该文件夹如果找不到，右键小狼毫输入法图标，选择用户文件夹确认即可打开。  初始时，该文件夹下只有下面几个东西：![](./Screenshots/custom_1.png)

   放入4个文件后，右键任务栏小狼毫图标，选择“重新部署”

   ![](./Screenshots/use_7.png)

   几秒钟部署成功，然后再右键图标，选择“输入法设定“，取消勾选自带的所有输入法，选中新出现的名字叫"zy"的输入法，点击”中“。

   ![](./Screenshots/use_8.png)

   至此完成所有的定制设置，可以使用该输入法打字了。

#### 使用效果

![](./Screenshots/use_30.png)
![](./Screenshots/use_24.png)

![](./Screenshots/use_25.png)

![](./Screenshots/use_26.png)

最重要的一点，可以自定义输入习惯：

![](./Screenshots/1.gif)

---

![](./Screenshots/2.gif)

解释：由于本人经常打“xiazai”的时候打成"xaizai" 所以定义了ia=ai

另外 en = eng eng = en

至于更详细的说明，请见[README.old.md](./README.old.md)文件说明。

由于时间仓促和水平所限，该输入方案还有很多不完善的地方，或者有很多不符合个人输入习惯的地方，如果你有

1. 任何bug反馈
2. 任何修改建议
3. 任何个人定制需求

都可以直接在github上提`issues`或者`pull request`，或者发邮件给我（yzc35326@gmail.com）！