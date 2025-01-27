# 获取百度翻译官方接口的步骤

获取百度翻译官方接口的过程大约需要 5 分钟。百度翻译官方接口有两个版本：标准版和高级版。**标准版完全免费**，但它每秒只能获取一次翻译结果，导致偶尔会出现翻译较慢的情况（例如翻译中文或三击选段时）；你也可以申请高级版，**高级版每月前 200 万字符免费，超出的部分会按照 49 元 / 百万字符收取费用，费用由百度翻译在它自己的[百度翻译开放平台](https://fanyi-api.baidu.com/)收取，与划词翻译无关**，但它每秒可以获取 10 次翻译结果，所以不会出现翻译较慢的情况。详细介绍见[百度翻译官方接口定价文档](https://fanyi-api.baidu.com/product/112)。

## 第一步：登录百度翻译开放平台

打开百度翻译开放平台 [https://fanyi-api.baidu.com/](https://fanyi-api.baidu.com/) 并登录你的百度账号，登录成功后点击「管理控制台」。

![划词翻译申请百度翻译官方接口第一步](./.vuepress/public/baidu-api-1.png)

## 第二步：注册成为百度翻译开发者

第一次进入管理控制台会让你注册成为百度翻译开发者，如下图。选择「个人开发者」并填写表单后点击「下一步」。**注册成功后会让你进行身份认证，点击「取消」就行。**

![划词翻译申请百度翻译官方接口第二步](./.vuepress/public/baidu-api-step-2.png)

## 第三步：开通「通用翻译服务」

注册成功后，打开控制台 [https://fanyi-api.baidu.com/api/trans/product/desktop](https://fanyi-api.baidu.com/api/trans/product/desktop)，点击「立即开通」按钮，然后：

1. 选择「通用翻译（适用于文本翻译）」并点击「下一步」
2. 选择「开通标准版」
3. 填写应用名称"划词翻译"然后点击「提交申请」，会提示「开通成功」

## 可选步骤：使用高级版接口

完成前三个步骤之后，你就可以使用标准版接口了，但如果你想使用高级版接口，可以打开百度翻译开放平台控制台 [https://fanyi-api.baidu.com/api/trans/product/desktop](https://fanyi-api.baidu.com/api/trans/product/desktop)，点击写有「标准版」的下拉框即可切换为高级版。第一次切换为高级版的时候会让你进行身份认证。

## 第四步：在划词翻译中填写百度翻译 APP ID 和密钥

打开百度翻译开放平台控制台 [https://fanyi-api.baidu.com/api/trans/product/desktop](https://fanyi-api.baidu.com/api/trans/product/desktop)，将页面最底部的「APP ID」和「密钥」填写进划词翻译的「设置页」-「翻译源」-「百度翻译」中。