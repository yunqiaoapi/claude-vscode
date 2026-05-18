# claude-vscode
# 在Vscode编辑器中集成Claude code插件，保姆级教程，简直编程对话统计文档的闺蜜

<img width="1920" height="1030" alt="bd4f8b28-f826-4f68-a4ce-1f2d0ffa595a" src="https://github.com/user-attachments/assets/f77525c9-c564-445f-b157-517ab7f0cdb5" />

# VSCode & Claude code<font style="color:#8A8F8D;"> </font>插件
## 准备工作
在开始之前，请确保你手边已经有了这三样东西（如果缺少，请先去获取）：

**API Key (密钥)：这个是您在令牌领取教程兑换出来的令牌**

```bash
sk-518GatoLXXXXXXXXXXXXXXXXXXXXXXXXsSLYe0zsnPH5
```

**Base URL (中转接口地址)：这个是我们固定的中转接口：**[**https://yunqiaoapi.com**](https://yunqiaoapi.com)

<font style="color:#DF2A3F;">（复制的时候看看前后有没有空格，要确保没有空格，否则使用的时候会报错）</font>

```bash
https://yunqiaoapi.com
```

## 安装VSCode
<font style="color:#000000;">第一步</font>：下载安装包 (官网)

请务必去官网下载，不要去第三方软件园，以免下载到被篡改的版本。<font style="color:#DF2A3F;">  
</font>**<font style="color:#DF2A3F;"> </font>**[**VSCode官网地址（https://code.visualstudio.com/）**](https://code.visualstudio.com/)

操作： 点击首页大大的蓝色按钮 "Download" 或者点击 "Download for Windows"（下载到现在你的系统）

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773382657468-7e5ed1ef-80ef-4dfd-bbd6-13ad506613f3.png)

第二步，安装步骤

如果您是 Windows 用户，点击Windows下载  
如果您是macOS 用户，点击MAC下载

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/63327424/1768299832712-ba121a5d-267e-4d5e-8453-ee204b3b7684.jpeg)

<font style="color:#DF2A3F;"></font><!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/63327424/1768299832712-ba121a5d-267e-4d5e-8453-ee204b3b7684.jpeg)

运行安装包： 双击下载好的 .exe 文件

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/63327424/1768300166272-6c490341-ea3a-482e-8942-2c2bb950e618.jpeg)

同意协议： 勾选“我同意此协议”，点击“下一步”

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/63327424/1768300263926-8cda26ce-5853-4778-958c-b6db16469f37.jpeg)

安装路径： 默认即可（通常在 C 盘），也可以改到 D 盘  
⚠️ 关键步骤（必看）： 在“选择附加任务”这一步，建议全部勾选！

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/63327424/1768300460523-7dab1aa0-d6f3-4ea0-86ab-e4d277e04a9f.jpeg)

<font style="color:#DF2A3F;">  
</font>完成： 点击“安装”，最后点击“完成”

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/jpeg/63327424/1768300510924-ab7063cf-c84b-48a2-b519-68e801d55aa6.jpeg)<font style="color:#DF2A3F;">  
</font>到这里已经完成了。



## 安装中文插件
**1.如果您觉得英文太复杂，您可以按照一个中文插件改成中文**

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773394681749-a4438dda-065e-46cd-88fa-48f5b9a180c3.png)

<font style="color:#DF2A3F;">注意：</font>

安装过程中会有一步这样的英文：<!-- 这是一张图片，ocr 内容为：点击 信任发布者和安装 了解详细信息 取消 -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773394976395-ecca9eb2-d289-4432-805f-31fe6d81a405.png)

**（上图是中文版的，点击蓝色的按钮即可）**

****

**2.安装完后点击右下角重启**

<!-- 这是一张图片，ocr 内容为：B Q AL GAME (ADMINISTRATOR] 米 日 B EXTENSION:CHINESE (SIMPLIFIED)(简体中文) LANQUAGE PACK FOR VISUAL STUDIO CODE X EXTENSIONS:MARKETPLACE 文 CHINESE ED)(简体中文) LANGUAGE PACK FOR VISUAL STUDIO CHINESE(SIMPLIFIED) CLINE CHINESE 1803MS MICROSOFT MICROSOFT.COM 49,020,435 您的IDE中的自主编码助手,能够... LANGUAGE PACK EXTENSION FOR CHINESE(SIMPLIFIED) 本 HYBRIDTALENTCOMPUTING .. AUTO UPDATE 空 ROO CODE CHINESE(原R....... 900MS UNINSTALL ROO CODE中文汉化版,在您的编辑... 中 HYBRID TALENTCOMPUTING CHANGELOG CHINESE(SIMPLIFIED)(简体中文) LA... MARKETPLACE 中文(简体) 适用于VS CODE 的中文(简体)          CODE 的中文(简体)      语言包 字 MICROSOFT IDENTIFIER MS-CEINTL.VSCODE- LANGUAGE-PACK-ZH CHINESE(TRADITIONAL)......4.5M 中文(繁酸 此中文(简体) 语言包为VS CODE 提供本地化界面. 1,110,2026031109 VERSION MICROSOFT INSTALL 使用方法 PUBLISHED 7 YEARS AGO ESLINT CHINESE RULES 145K 1 DAY AGO LAST RELEASED ES ESLINT中文规则提示插件 通过使用"CONFIGURE DISPLAY LANGUAGE"命令显式设置VS CODE 显示语言,可以替代影认UI 语言.按 LINTJ MAGGIE 下CH+SHIN+P(组合键以显示:命令面板*,命令面板",然后键入'DISPLAY 以筛选并显示[CONFIGUAGE"命令. CATEGORIES 按ENTER,然后会校区域设育显示安装的语言列表,并突出是示当前语言设置.选择另一个一语言"以切换UI语 CHINESE(SIMPLIFIED,... 24K 言.请参阅文档并获取更多信息. CHINESE(SIMPLIFIED.CHINA)LANGUAG... LANQUAGE PACKS MICROSOFT 参与 C 35K CHINESE TRANSLATION RESOURCES 繁 有关翻译改进的反馈,请在VSCODE-有储库中创建问题.翻译字符串在MICROSOFT本地化平台中维护.只能 TRANSLATES BETWEEN TRADITIONAL AND..... COMPULIM 在MICROSOFT本地化平台中进行更改,然后才能导出到VSCODE-LOC存储库.因此, VSCODE-LOC存储库中不接受拉 INSTALL REPOSITORY ISSUES 取请求 CHINESE LOREM 49K 汉 LICENSE 简体中文的乱数假文 许可证 MICROSOFT CATLAIR INSTALL MARKETPLACE 安装后点击重启 源代码和字符串使用MIT许可进行授权. CHINESE LOREM 643K 繁 TRADITIONAL CHINESE LOREM 感谢 KEVIN YANG INSTALL MATPLOTLIBPILOT(CHIN......              此中文(简体)语言包是"来自社区,奉献社区"的社区本地化工作的成果. 提供MATPLOTLIB代码片段,模板等工具 XX WOULD YOU LIKE TO CHANGE VISUAL ST.TIO CODE'S DISPLAY 特别感谢社区中每一位向这个项目做出贡献的朋友. LITCHI INSTALL LANGUAGE TO CHINESE SIMPLIFIED AND RESTART? CHINESE COLORS CO25K 杰出贡献者: 中国传统色彩色卡,并提供颜色代.. CHANGE LANQUAGE AND RESTART JOEL YANG:在此项目向社区开放之后,翻译了大部分新增字符串.先后翻译了47 INSTALL TAIYUUKD -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773394798813-f3b71753-5cc6-440c-87c8-3cf814925a63.png)

自动重启后就是中文版的了



## 安装Claude code并配置
打开vs code点击左侧边栏的扩展<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773385023920-c0925163-b540-4912-8480-5a1f2969113b.png)

搜索：Claude code并安装，点击<font style="color:#FFFFFF;background-color:#117CEE;">信任发布者和安装</font>开始安装

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773374562459-13e2a070-1042-48a7-a6a8-c9e3e1715bf9.png)

安装完之后

**第一步：**点击左下角小齿轮

**第二步：**点击设置（win快捷键Ctrl+，）（mac快捷键Cmd+，）

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773375214474-79d5c8e8-5480-4d1f-a76e-768b30ae8be0.png)



**打开之后**

**第一步：**在顶部的搜索框里直接搜索：Claude Code Environment  
**第二步：**找到 "Claude Code: Environment Variables" 这一项，点击它下面的 “在 settings.json 中编辑” (Edit in settings.json)。  
 

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773375327943-a2c6c3ef-b634-47b6-96c2-45c30db68203.png)



### 打开后
新设备第一次开始打开的配置是这样的

**<font style="color:#DF2A3F;">注意</font>**：如果您们之前配置过别家的东西，或者是别的ai的配置，需要删掉，不然会有冲突 接不上



<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773375529369-8541e9da-fad8-44b5-a7d3-1fa13eb9f99c.png)



### 接下来：填入内容
为了绝对不出错，直接把截图里的第 1 行到第 5 行**全部删掉**，**（根据个人情况删除之前的配置，确保与我们的配置不会冲突）**然后直接把我下面这段完整的代码复制粘贴进去（记得把里面的sk开头的换成您去令牌获取的密钥）：

```bash
{
  "claudeCode.disableLoginPrompt": true,
  // 禁用登录提示
  "claudeCode.environmentVariables": [
    {
      "name": "CLAUDE_CODE_OAUTH_TOKEN",
      "value": "替换成令牌，sk开头的API密钥"  
    },
    {
      "name": "ANTHROPIC_BASE_URL",
      "value": "https://yunqiaoapi.com" 
    },
    {
      "name": "CLAUDE_CODE_DISABLE_NONESSENTIAL_TRAFFIC",
      "value": "1" 
  // 一键关闭 Claude Code 向 Anthropic 发送的所有非核心网络请求，更少的后台流量
    }
  ]
  
}
```

_<font style="color:#DF2A3F;">旧版 ANTHROPIC_AUTH_TOKEN 已弃用</font>_



填完之后再上面可以看到有个小圆点，按 `Ctrl + S` 确保文件上面那个小白点消失（代表保存成功

保存完之后关掉一整个vs code重新打开

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773719377117-89d7ceda-98c4-4f79-b81d-e0ae73ec1c65.png)

重新打开之后输入”你好“运行一下试试



### <font style="color:#DF2A3F;">第一注意事项！！！</font>
**<font style="color:#DF2A3F;">如果输入对话之后就看以下步骤，如果没有就跳过此步骤</font>**

输入之后如果跳出这个之后就点击“Skip for now”

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773472609792-b8a9663e-5d28-4145-8081-790f231ca294.png)



**点击“Skip fornow”之后就会出现对话内容**

**这句话代表着你缺少了GitHub**

**看下一步“****<font style="color:#DF2A3F;">第二注意事项</font>****”下载安装Git**

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773472877302-e812b4f6-1a98-4d8c-879e-b1e5506be54d.png)



### <font style="color:#DF2A3F;">第二注意事项！！！</font>
重新打开之后如果出现以下报错

 这段红字开头写着：`Error: Claude Code on Windows requires git-bash`

** ****Claude Code 这个插件在咱们 Windows 电脑上干活时，必须借用一个叫 Git 的底层工具 **

**您只是缺少了这个Git**

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773382945028-7efe952f-a630-4de9-9f75-6335bc9d4a53.png)



1. ** 第一步：下载 Git 工具  **

 您直接在浏览器里打开这个官方链接并下载：[**https://git-scm.com/downloads/win**](https://git-scm.com/downloads/win)

+ 点击 "Download for Windows" 下载安装包
+ 下载完后运行下载的 .exe 安装文件
+ **极其关键：安装过程中您什么设置都不需要改！** 就无脑疯狂点击右下角的 **“Next（下一步）”**，一直点到最后完成安装。  

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773384072884-cb91a816-2d8a-4a25-b2be-38a932acc1bc.png)

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773384236335-1828d4ec-ac8c-4039-ac7a-0f54f5ffab6c.png)



2.  安装完Git之后重新打开vs code中的Claude code插件

输入”你好“运行一下

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773384795737-35e64b18-25fe-4e18-bfd4-0aa474cb4951.png)



### 切换模型方法
在对话框输入：/model

然后回车

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773386156667-0b23e09e-e534-418a-9863-1229516b5d73.png)



用上下键选择模型，然后回车选定就行了

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773386224806-bad99980-0e50-4844-8e33-fa39b49aca2b.png)

最后输入你好测试一下！

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773386744632-e4b97b25-7a88-4d4d-ac24-22c80bee0ee4.png)



### <font style="color:rgb(52, 64, 84);">如果显示登陆页面可以通过系统环境变量配置</font>
**<font style="color:rgb(52, 64, 84);">为了让 Claude Code 连接到你的中转服务，需要设置几个环境变量：</font>**

**<font style="color:rgb(52, 64, 84);">图形界面配置（推荐）</font>**<font style="color:rgb(52, 64, 84);">右键</font>`<font style="color:rgb(52, 64, 84);">【此电脑】->【属性】->【高级系统设置】->【环境变量】</font>`

<font style="color:rgb(52, 64, 84);">新建用户变量</font>

<font style="color:rgb(52, 64, 84);">A</font><font style="color:#DF2A3F;">NTHROPIC_AUTH_TOKEN: sk-XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</font>

<font style="color:#DF2A3F;">ANTHROPIC_BASE_URL: </font>[<font style="color:#DF2A3F;background-color:#FBDE28;">https://yunqiaoapi.com</font>](https://yunqiaoapi.com)

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773658861532-69a57e26-de0b-4d25-bf40-93f4280b81c4.png)

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/67472675/1777365505317-28d01d7a-284c-4ae5-a0a7-9e31caa43411.png)

<!-- 这是一张图片，ocr 内容为： -->
![](https://cdn.nlark.com/yuque/0/2026/png/63327424/1773658886671-144d18e5-25ae-41be-802b-be29a1f843b6.png)



## 额外补充
如果实在配置Claude Code插件不成功（配置过其他家的API），预计需要安装Claude Code本体才能解决这个问题了。



