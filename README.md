可能是墙内最强 AI 教学

# 目录

- [目录](#目录)
- [前言](#前言)
  - [GFW 与 CloseAI，墙内之痛](#gfw-与-closeai墙内之痛)
  - [了解 OpenAI LLMs](#了解-openai-llms)
  - [Princing](#princing)
- [初阶：ChatGPT](#初阶chatgpt)
  - [**_!IMPORTANT!_** 为什么不推荐购买 OpenAI 账号和营利性 ChatGPT 镜像](#important-为什么不推荐购买-openai-账号和营利性-chatgpt-镜像)
    - [封号风险](#封号风险)
    - [暴利行业](#暴利行业)
  - [网络环境](#网络环境)
  - [有效邮箱](#有效邮箱)
  - [海外电话](#海外电话)
  - [注册过程中可能遇到的问题](#注册过程中可能遇到的问题)
  - [使用 ChatGPT](#使用-chatgpt)
  - [_**Optional\***_ ChatGPT Plus](#optional-chatgpt-plus)
- [初阶：New Bing](#初阶new-bing)
- [初阶：GitHub Copilot](#初阶github-copilot)
  - [Host 代理引发的错误](#host-代理引发的错误)
- [中阶：通过 API 访问 OpenAI 服务](#中阶通过-api-访问-openai-服务)
  - [代表性 API 应用 Preview](#代表性-api-应用-preview)
    - [ChatGPT 学术优化](#chatgpt-学术优化)
    - [ChatGPT - Genie AI](#chatgpt---genie-ai)
    - [Interactive Simulacra of Human Behavior](#interactive-simulacra-of-human-behavior)
  - [申请 API key](#申请-api-key)
  - [使用 OpenAI API](#使用-openai-api)
    - [VScode: ChatGPT-Genie](#vscode-chatgpt-genie)
    - [Android: Alissu GPT](#android-alissu-gpt)
- [高阶：部署墙内可用的 ChatGPT “镜像”](#高阶部署墙内可用的-chatgpt-镜像)
  - [前置条件](#前置条件)
  - [一键部署](#一键部署)
  - [添加 API key](#添加-api-key)
  - [**_Optional\*_** 更换模型和 Base URL](#optional-更换模型和-base-url)
- [高阶：Azure OpenAI](#高阶azure-openai)
  - [Azure 学生认证](#azure-学生认证)
  - [申请 Azure GPT-3.5 API](#申请-azure-gpt-35-api)
  - [部署 Azure OpenAI 服务](#部署-azure-openai-服务)
  - [部署 Azure OpenAI 模型](#部署-azure-openai-模型)
  - [获取 Azure OpenAI API key](#获取-azure-openai-api-key)
  - [用 VScode Genie 调用 Azure OpenAI API](#用-vscode-genie-调用-azure-openai-api)
- [高阶：部署基于 LLM 的聊天 bots](#高阶部署基于-llm-的聊天-bots)
- [Bonus Parts:](#bonus-parts)
  - [开发基于 LLMs 的应用](#开发基于-llms-的应用)
  - [GitHub 学生认证指南](#github-学生认证指南)
  - [用大陆 +86 手机号注册 Gmail](#用大陆-86-手机号注册-gmail)

# 前言

标题有点水，但请相信我，文章内容足够硬核，流程足够详细，绝对值得一看。本文将分几个部分向墙内用户介绍 OpenAI LLMs 服务：

- 前言中将介绍国内用户使用 OpenAI 产品的几个须知
- 初阶难度将介绍三个标志性的 ai 产品
- 中阶难度将举例介绍使用 OpenAI API 的两种方式
- 高阶难度将介绍两种免翻墙使用 OpenAI API 的方法
- Bonus parts 则是一些与正文内容关联略小但能帮助理解的部分

希望能帮到各位，~~点赞关注收藏不迷路~~

**_To be continued..._** 意味着笔者暂时还没想好这块怎么写……如果你有什么特别想看的部分或提建议或也欢迎在评论区提 issue 或 pull request

## GFW 与 CloseAI，墙内之痛

先放几张国内用户一眼血压升高的图片：

![can not reach page](/resource/can%20not%20reach.png)  
_Can not Reach Page. 你被 GFW 拦住了。这里不作赘述_ **_so fuck you GFW : )_**

![checking browser](/resource/checking%20browser.png)  
_Checking Browser. 验证你是否为爬虫，或者从浏览器 cookies 等蛛丝马迹中判断你是否在不支持 OpenAI 服务的地区_

![access denied](/resource/denied.png)  
_Access Denied_

![Unavailable in Your Country](/resource/country.png)  
_Service Unavailable in Your Country_ **_so fuck you CloseAI : )_**

![API failed](/resource/api%20failed.png)  
_gpt API 网络请求失败_

（已过滤），你就很难通过 CloseAI 堪比 Netflix 的 ip 封锁；没有基本的网络常识，你也很难绕过 CloseAI 额外的浏览器检测。因此，不翻墙使用 gpt 服务变得吃香，部分商家利用信息差向不提供 OpenAI 服务的地区高价兜售 OpenAI 服务，令人作呕，这是我写这篇文章的原因之一

## 了解 OpenAI LLMs

这部分我大概想介绍下不同 LLM 之间的定价和擅长工作等区别
**_To be continued..._**

Reference: [Models - OpenAI API Documentation](https://platform.OpenAI.com/docs/models)

## Princing

**_To be continued..._**

Reference: [Pricing -OpenAI API Documentation](https://OpenAI.com/pricing)

# 初阶：ChatGPT

## **_!IMPORTANT!_** 为什么不推荐购买 OpenAI 账号和营利性 ChatGPT 镜像

### 封号风险

网购 OpenAI 账号（包括代注册）往往来源于批量注册，一个 ip 地址注册多个 OpenAI 账号的后果就是被“秋后算账”封号，商家一跑了之，毫无商业诚信可言

![account banned](/resource/banned.png)  
_你号没了_

### 暴利行业

无论是兜售 OpenAI 账号还是出售“问答次数”等服务都是暴利！根据[《GPT-4 API 接口调用及价格分析》](http://t.csdn.cn/3Okc8)，让价格高昂的 GPT-4 回复 2000 多字通常只需要 1 人民币左右，而更常用的 ChatGPT 只要 4 分钱不到！信息差使得国内营利性 ChatGPT 镜像完全成了割墙内人韭菜的暴利灰产

![price](/resource/price.png)  
_直观地看出调用 GPT 接口的定价_

## 网络环境

- 已过滤

  已过滤

- 值得注意的是，CloseAI 封禁节点的力度相当之大，因此机场出现无法解锁 CloseAI 服务而 [Access Denied](#access-denied-||-Unavailable-in-Your-Country) 的情况非常常见

  ![GlaDOS unlock failed](/resource/GlaDOS%20failed.png)  
  _GlaDOS 解锁 OpenAI 是不稳定的_

- 由于机场跑路的情况非常常见，因此最好常备多个机场，能买不限时流量计费就买流量，不是看流媒体通常速度不要紧。可以在这里查看机场解锁 OpenAI 情况 [DuyaoSS 的 Telegram 频道](https://t.me/DuyaoSS)

  ![airports example](/resource/airport%20test.png)  
  _Access Denied 99% 是节点问题_

- 浏览器环境对你能否进入 OpenAI 网站至关重要，当你切换了多个节点或更换机场后仍然遇到 [Access Denied 错误](#access-denied-||-Unavailable-in-Your-Country) 时，可以试着清除浏览器 cookies、更换浏览器或使用无痕浏览

  ![clear cookies](/resource/clear%20cookies.png)  
  _以 Edge 为例，在浏览器地址栏输入 edge://settings/clearBrowserData， 选中并清除浏览器 cookies_

  ![inprivate](/resource/inprivate.png)  
  _`Crtl`+`Shift`+`N`，无痕浏览模式不会保存你的 cookies_

## 有效邮箱

某月某日以来，OpenAI 先后禁止了 163mail、qqmail 甚至是 outlook 邮箱（即微软账号，CloseAI 急起来连它爹都封）的注册，因此你需要一个有效的邮箱来注册 OpenAI 账号，通常推荐用 gmail 注册（edu.cn 邮箱我没试过，听说似乎也可行）

[《如何使用 +86 大陆手机号注册 Gmail》](#bonus如何用大陆-86-手机号注册-gmail)

## 海外电话

如果你没有实体海外电话，推荐使用 [sms-activate.org](https://sms-activate.org/) 购买虚拟电话验证服务（俗称接码）

1. 注册 sms-activate.org 账号并充值一点钱（一般最低充值金额就够了）

2. 根据你节点所在地区购买 OpenAI 虚拟电话接码服务（上次我用美国手机号被 CloseAI 发现是虚拟手机号 ban 了，改用英国的手机号才成功）

   ![sms step1](/resource/sms1.png)  
   _找到 OpenAI_

   ![sms step2](/resource/sms2.png)  
   _比较推荐英国地区，价格实惠_

   ![sms step3](/resource/sms3.png)  
   _别担心，20 分钟未收到短信或手动取消服务都会自动退款 👍_

3. 复制手机号，去 [OpenAI 官网](https://platform.OpenAI.com) 一步步注册。将 sms-activate.org 提供的虚拟手机号复制到 OpenAI 的电话号码输入框中

   ![sms step4](/resource/sms4.png)  
   _记得删除国家前缀（如 +44 英国）_

4. 注册成功！开始使用

## 注册过程中可能遇到的问题

![sign up problem1](/resource/signup%20problem.png)  
_账号被怀疑参与非法行为。代理节点和你的手机号需处于同一国家_

![sign up problem2](/resource/virtual%20phone.png)  
_你的手机号被鉴定为虚拟手机号。退款（未收到验证码可以直接点击“X”取消），换个国家的手机号_

**_To be continued_**

如果出现其他问题，可以参考[《你注册 OpenAI 时为什么会失败》](https://sms-activate.org/blog/how-to-sign-up-for-ChatGPT)

## 使用 ChatGPT

[ChatGPT playground](https://chat.OpenAI.com/) 是一个不需要 API 接口就可以直接使用的 OpenAI 官方产品，它提供了一个简单的聊天界面

![ChatGPT register](/resource/chatgpt%20register.png)  
_高情商 chatbot 👍_

## _**Optional\***_ ChatGPT Plus

![ChatGPT plus](/resource/chatgpt%20plus.png)  
_ChatGPT 和其他使用 API 的模型不同，前者属于一个成熟的产品，而后者则是主要面向开发者的服务。因此其付费版的价格也相对昂贵（得多）_

ChatGPT Plus 是 OpenAI 官方提供的付费服务，它提供了：

1. 更快的回应速度（相较于 ChatGPT，不过还是绝对慢于 Azure OpenAI API）
2. 拥堵时仍能使用（不会被 Rate Limited）
3. GPT-4 免费试用（每 4h 100 次）

不过其实我个人并不推荐墙内用户购买 ChatGPT Plus，因为：

1. 价格昂贵（每月 20 USD，拼车还容易遇到各种问题）
2. 需要海外信用卡（麻烦，虚拟信用卡还容易多交钱）
3. 墙内访问麻烦（要过浏览器验证）

**_To be continued..._**

# 初阶：New Bing

1. 首先你需要一个微软账号，用大家的 edu 邮箱或者自己私人邮箱就行，不作赘述

2. 在官网 [下载 Edge dev](https://www.microsoftedgeinsider.com/zh-cn/download/dev) 并安装

3. 科学上网后打开 Edge dev，点击右边上角必应图标，会弹出申请按钮，登录微软账号加入等待列表

   ![New Bing ico](/resource/new%20bing.webp)  
   _如果不翻墙访问的话这个 icon 不会显示 New Bing_

4. 申请成功后会收到邮件

   ![in waitlist](/resource/nb%20waitlist.png)  
   _已经在 waitlist 里了，但通过时间差别挺大，从一天到半个月不等_

5. 等待微软通过后，你会收到欢迎邮件，你就可以使用新必应。等候时间因人而异（奇怪的是笔者从未受到过欢迎邮件，资格倒确实通过了）

6. 资格通过后，你不需要 Edge dev 而只需要发布版 Edge 就可以愉快使用 New Bing（Edge dev 的圆角界面是哪个天才想出来的，太恶心了！）

   ![chat with New Bing](/resource/nb%20chat.png)  
   _国内访问 New Bing 比 [ChatGPT playground](https://chat.openai.com/) 方便多了_

# 初阶：GitHub Copilot

![GitHub Copilot](/resource/github%20copilot.png)  
_GitHub Copilot shares recommendations based on the project's context and style conventions. Quickly cycle through lines of code, complete function suggestions, and decide which to accept, reject, or edit_

以 VScode 为例，在日常文字/代码工作中使用 GitHub Copilot 与其 experimental features _**Optional\***_

![GitHub edu](/resource/github%20edu.png)  
_首先你需要一个已 [通过 GitHub 学生认证](#GitHub-学生认证指南) 的 GitHub 账号（愿意直接掏钱买的大佬除外）_

![VScode](/resource/vscode.png)  
_[下载 VScode](https://code.visualstudio.com/Download)（当然其他支持 Copilot 的 IDE 也行）_

![VScode Copilot](/resource/copilot.png)  
_安装 GitHub Copilot 插件和 experienmental features（可能会有一些简单的验证步骤）_

![using Copilot](/resource/using%20copilot.png)  
_开始使用 Copilot 吧 🎉_

## Host 代理引发的错误

某些 host 代理比如 Watt Toolkit 的 GitHub API 加速功能和 Copilot 冲突，使用时需将其关闭

![problem](/resource/copilot%20problem.png)  
_Watt Toolkit host 代理加速 GitHub 引发的错误_

![conflict](/resource/copilot%20api.png)  
_取消勾选该项即可_

# 中阶：通过 API 访问 OpenAI 服务

API 是几乎所有基于 OpenAI 服务的应用程序的基础，该部分将举例说明使用 gpt API 的情景和方法。该部分要求你已经拥有一个 OpenAI 账号

## 代表性 API 应用 Preview

先来看看几个 API 应用的效果：

### ChatGPT 学术优化

![ChatGPT academic](/resource/chatgpt%20academic.gif)  
_其实它还支持除 ChatGPT 以外的多种 LLM（大型语言模型）_

[ChatGPT-academic](/resource/https://github.com/binary-husky/ChatGPT_academic) 是科研工作专用 ChatGPT 拓展，特别优化学术 Paper 润色体验，支持自定义快捷按钮，支持自定义函数插件，支持 markdown 代码块表格显示，Tex 公式双显示，有 Python/C++项目剖析/自译解功能，PDF/LaTex 论文翻译/总结功能，兼容 ChatGLM 等本地模型

### ChatGPT - Genie AI

![ChatGPT - Genie AI](/resource/genie%20gui.png)  
_[获取效果预览视频.mp4](/resource/api.mp4)_

[ChatGPT - Genie AI](https://marketplace.visualstudio.com/items?itemName=genieai.ChatGPT-vscode) is Your best AI pair programmer. Save conversations and continue any time. A Visual Studio Code - ChatGPT Integration. Supports GPT-4, GPT3.5, GPT3 and Codex models. Create new files, view diffs with one click; your Copilot to learn code, add tests, find bugs and more

### Interactive Simulacra of Human Behavior

> ![game demo](/resource/chatgpt%20town.jpg)  
> Generative agents create believable simulacra of human behavior for interactive applications

Park, J.S., O'Brien, J.C., Cai, C.J., Morris, M.R., Liang, P. and Bernstein, M.S., 2023. Generative Agents: Interactive Simulacra of Human Behavior. arXiv preprint arXiv:2304.03442.

[view on arxiv.org](https://arxiv.org/abs/2304.03442)
[view pdf](ChatGPT%20town.pdf)
[play game demo](https://reverie.herokuapp.com/arXiv_Demo/)

## 申请 API key

3 月前注册的 OpenAI 账户一般有 18 美元免费额度，有效期至 6 月 30 日；而 3 月 1 日之后注册的账号免费额度只有 5 美元，有效期到 7 月，注册时间往后推移，有效期也会向后推移。这些钱将是你接下来使用基于 API 的 OpenAI 服务的基础（有海外信用卡的大佬除外），你将开始使用 API 来访问 OpenAI 服务。从创建 API key 开始

![create API key](/resource/create%20api.png)  
_在 OpenAI 官网 [创建和管理 API key](https://platform.openai.com/account/api-keys)_

![view API](/resource/api%20view.png)  
_复制 API key_ **_注意：请妥善保存你的 API key，因为你将再也看不见它_**

![API usage](/resource/api%20usage.png)
_你可以在 [account > usage](https://platform.openai.com/account/usage) 处管理你的 API key，免费账户的额度会自动过期_

## 使用 OpenAI API

> 你可以用任何语言通过 HTTP 请求与 API 进行交互，使用我们的官方 Python 接口、官方 Node.js 库或由社区维护的库
> https://platform.OpenAI.com/docs/API-reference

### VScode: ChatGPT-Genie

该部分面向使用 VScode 的用户，以 [VScode Genie AI 插件](https://marketplace.visualstudio.com/items?itemName=genieai.ChatGPT-vscode) 为例介绍如何使用 OpenAI API

1. 安装 VScode 插件

   ![find genie](/resource/genie.png)  
   _找到并安装 ChatGPT - Genie AI 插件，成功后会在左侧显示 Genie 图标_

2. 输入 API key

   ![change API](/resource/change%20api.png)  
   _在这里输入你的以 sk-开头的 API key_

3. _**Optional\***_ 优化插件设置

   找到 VScode 设置文件 setting.json（通常在 C:\Users\用户名\AppData\Roaming\Code\User\settings.json），在最外层的花括号中输入以下设置或按需在 GUI 中修改 Genie 插件设置

   ```json
   // 自定义对话精灵名称（你最好不认识她它）
   "genieai.personalizedName": "Neuro-sama",

   // 禁用不常用功能
   "genieai.promptPrefix.completeCode-enabled": false,
   "genieai.promptPrefix.addComments-enabled": false,
   "genieai.promptPrefix.addTests-enabled": false,
   "genieai.promptPrefix.findProblems-enabled": false,

   // 开启自定义前缀（我定义了中英互译）
   "genieai.promptPrefix.customPrompt1-enabled": true,
   "genieai.promptPrefix.customPrompt1": "Translate to Chinese",
   "genieai.promptPrefix.customPrompt2-enabled": true,
   "genieai.promptPrefix.customPrompt2": "Translate to English",

   // 允许储存对话记录
   "genieai.enableConversationHistory": true,
   ```

   ![edit shortcuts](/resource/edit%20shortcuts.png)  
   _进入 VScode 快捷键编辑 GUI_

   ![edit genie shortcuts](/resource/genie%20shortcuts.png)  
   _搜索 genie，修改你想要的快捷键。以上是我个人的绑键策略_

4. 开始使用

   [配置科学上网环境](#网络环境) ，但使用 API 时无需担心浏览器环境！

   ![genie](/resource/genie%20gui.png)  
   _[给项目点个 Star](https://GitHub.com/ai-genie/ChatGPT-vscode)_

### Android: Alissu GPT

[Alissu: Chat with AI](https://play.google.com/store/apps/details?id=com.ekmen.aiapp&hl=zh-cn) 是 Google Play 中最受欢迎，最简洁，最方便的基于 OpenAI API 的安卓 gpt 应用之一。该项目允许你使用公共 API key 进行少量临时的查询，但你也可以上传自己的 API key（据其团队称不会云储存用户的 API key，但由于其似乎并非开源项目因此对 API 保密有特别高需求的同学应谨慎对待）来无限制使用 Davinci 等更昂贵的模型，获取更多的查询次数并大幅减少广告

![Alissu GPT](/resource/alissu.png)  
_在你的安卓设备上 [安装 Alissu](https://play.google.com/store/apps/details?id=com.ekmen.aiapp&hl=zh-cn)。如果你没有 google play，也可以 [从我的 Azure 容器中下载](/resource/cfa-2.5.12-premium-universal-release.apk)_

![Alissu GPT](/resource/alissu%20key.jpg)  
_点击右上角 ≡ 符号 Add Key，添加你的 Optnai API key（暂不支持 Azure OpenAI API）并修改你想用的模型（推荐 Turbo）_

相关教程：[在安卓手机上配置科学上网环境并安装谷歌服务](#在安卓手机上配置科学上网环境并安装谷歌服务)

# 高阶：部署墙内可用的 ChatGPT “镜像”

然而，每次总需要翻墙才能使用 gpt，这样的体验实在是太糟糕了。本文将介绍如何用 Netlify 托管部署你自己的 ChatGPT “镜像”，使你可以无需翻墙使用 gpt API，还可以让你不会翻墙的家人们随时使用 OpenAI 服务。GitHub 开源项目 [ChatGPT-demo](https://GitHub.com/ddiu8081/ChatGPT-demo) 已经为你做好了一个 ChatGPT 镜像网站，万事俱备，你只需要部署+上传自己的 API key 即可。此部分默认你拥有基础的网络常识，初步掌握使用 gpt API 的方法，并拥有一个 GitHub 账号。~~就算啥都没有也不要紧反正简单得很~~ (●'◡'●)╯︵ ┻━┻

先上用例：https://glittery-zabaione-7c5781.netlify.app/  
![ChatGPT demo](/resource/chatgpt%20demo.png)  
_我自己部署的公益项目，大家随便用_

## 前置条件

确保自己拥有一个可用的 GPT-3.5-Turbo API

[Netlify](https://app.netlify.com/) 是一家美国云计算公司，可以为用户提供静态网页托管服务

![Netlify signup](/resource/netlify%20signup.png)  
_用 GitHub 账号注册 Netlify，如果 GitHub 打不开可以用 [Watt Toolkit](https://steampp.net/) 加速_

## 一键部署

克隆开源 ChatGPT “镜像” [ChatGPT-demo](https://GitHub.com/ddiu8081/ChatGPT-demo) 到你的 GitHub repository 并部署服务

**[一键克隆+部署](https://app.netlify.com/start/deploy?repository=https://GitHub.com/ddiu8081/ChatGPT-demo#OpenAI_API_KEY=&HTTPS_PROXY=&OpenAI_API_BASE_URL=&HEAD_SCRIPTS=&SECRET_KEY=&OpenAI_API_MODEL=&SITE_PASSWORD=)**

![Netlify step1](/resource/netlify1.png)  
_链接到你的 GitHub_

![Netlify step2](/resource/netlify2.png)  
_给你的 repository 取个名_

![Netlify step3](/resource/netlify3.png)  
_等待部署完成（约 2 分钟）_

![Netlify step4](/resource/netlify4.png)  
_部署成功！_

## 添加 API key

我们还需要为网站添加 API key 来驱动它

![Netlify step5](/resource/netlify5.png)  
_打开部署设置_

![Netlify step6](/resource/netlify6.png)  
_打开环境变量界面_

![Netlify step7](/resource/netlify7.png)  
_找到并修改 OpenAI_API_KEY 变量_

![Netlify step8](/resource/netlify8.png)  
_输入你自己的 API key 并保存_

![Netlify step9](/resource/netlify9.png)  
_恭喜你现在可以随时随地无需翻墙访问你自己的 ChatGPT “镜像”了_

## **_Optional\*_** 更换模型和 Base URL

本部分需要你提前掌握下一章节 Azure OpenAI 的内容，如果你不想了解，可以跳过这一部分。该部分将介绍如何更换 ChatGPT “镜像” 的模型和 Base URL，使你可以使用任何你想要的模型，或更换为 Azure OpenAI API

**_To be continued..._**

# 高阶：Azure OpenAI

现在我们再要用 GPT-3.5 已经不需要翻墙了，但可怜的 ~~Neuro-sama~~ ChatGPT Genie 还在墙内，使用起来不仅得翻墙，速度还慢，又经常出岔子。因此，我们隆重推出：**Macrohard Azure OpenAI**。它不仅墙内还直接可用，速度还比 OpenAI 的 API 快很多，甚至还有对学生每年整整 100 美刀的免费额度，~~甚至对于大型企业而言还大大提高了数据安全性和可控性（但这个你们应该不 care）~~！

**Let's start**

该部分以使用 Azure OpenAI API 取代原生 OpenAI API 使用 VScode Genie 插件为例介绍如何使用 Azure OpenAI API。此部分需要你拥有一定网络知识，掌握使用 gpt API 的方法，并拥有一个已通过 [GitHub 学生认证](#bonusGitHub-学生认证指南) 的 GitHub 账号

## Azure 学生认证

![Azure student](/resource/azure%20stu.png)  
_完成 [Azure 学生认证](https://Azure.microsoft.com/zh-cn/free/students/)_ **_前提是先通过 GitHub 学生认证！_**

![Welcome to Azure for Students](/resource/azure%20stu%20success.png)  
_申请通过后会受到一封确认邮件，其中包含你的 Subscription ID_

## 申请 Azure GPT-3.5 API

如实填写 [Azure GPT-3.5 申请表](https://aka.ms/oaiapply)，以下是几个需要稍微注意的地方：

![q3](/resource/azure%20q3.png)  
_有几个就填几个（通常是一个）_

![q4](/resource/azure%20q4.png)  
_把你邮件里的 Subscription ID 填进去_

![q5](/resource/azure%20q5.png)  
_用你高贵的 EDUmail 而不是私人邮箱_

![q6](/resource/azure%20q6.png)  
_你浙_

后面按需填就行，可惜我没法重新给你们变出一张表单提交成功的图来

## 部署 Azure OpenAI 服务

![create service](/resource/azure%20create.png)  
_进入 [Azure OpenAI dashboard](https://portal.Azure.com/#view/Microsoft_Azure_ProjectOxford/CognitiveServicesHub/~/OpenAI) 创建 OpenAI 服务_

![domain name failed](/resource/azure%20temp.png)  
_必须搞一个新域名，和 cc89 id 不能重复一个道理_

![domain name success](/resource/azure%20domain%20name.png)  
_按照这样填写（Region 随手选一个，Domain Name 当然没必要这么长，Pricing tier 你没得选）_

![network](/resource/azure%20network.png)  
_懂得都懂没啥好说的_

![submit](/resource/azure%20submit.png)  
_提交_

![deployment](/resource/azure%20deploying.png)  
_等候部署完成（约 5 分钟）_

![deploying](/resource/azure%20deployment.png)  
_部署成功！_

## 部署 Azure OpenAI 模型

![deploy model](/resource/azure%20model%20create.png)  
_待申请通过后（似乎没有邮件提醒，笔者 2 天内就通过了）创建模型，推荐 GPT-3.5-Turbo-0301（即 ChatGPT 的快照版本）。不同模型之间各有优劣，定价也天差地别。然而，谁能阻止你部署多个模型呢？_

## 获取 Azure OpenAI API key

回到 [Azure OpenAI dashboard](/resource/https://portal.Azure.com/#view/Microsoft_Azure_ProjectOxford/CognitiveServicesHub/~/OpenAI)

![choose service](/resource/azure%20openai%20dashboard.png)  
_选择你创建的服务_

![get keys](/resource/azure%20key.png)  
_获取一个 Azure OpenAI key 和 Endpoint_

## 用 VScode Genie 调用 Azure OpenAI API

![change API](/resource/change%20api.png)  
_在这里输入你的 Azure OpenAI API key，长度和 sk- 开头的原生 OpenAI API key 不一样_

打开 VScode 设置文件 setting.json（通常在 C:\Users\用户名\AppData\Roaming\Code\User\），在最外层的花括号中插入以下设置（需替换部分代码）或按需在 GUI 中修改 Genie 插件设置

```json
"genieai.OpenAI.model": "[模型名称]",
"genieai.OpenAI.maxTokens": "[自定义最大 tokens]", // 需小于最大 tokens
"genieai.OpenAI.APIBaseUrl": "[Endpoint]",
"genieai.Azure.url": "[Endpoint]/OpenAI/deployments/[模型名称][/Optional：调用方法]/completions?API-version=[你的 API 版本]",
```

**_Example:_**

```json
// 可以用注释来方便地替换多个预设
/*
"genieai.OpenAI.model": "text-davinci-003",
"genieai.OpenAI.maxTokens": 3800, // 最大 tokens: 4097
"genieai.OpenAI.APIBaseUrl": "https://sha1rholder-gpt.OpenAI.Azure.com",
"genieai.Azure.url": "https://sha1rholder-gpt.OpenAI.Azure.com/OpenAI/deployments/tdavinci3/completions?API-version=2023-03-15-preview"
*/

"genieai.OpenAI.model": "gpt-3.5-turbo-0301",
"genieai.OpenAI.maxTokens": 16000, // 最大 tokens: 16384
"genieai.OpenAI.APIBaseUrl": "https://sha1rholder-gpt.OpenAI.Azure.com",
"genieai.Azure.url": "https://sha1rholder-gpt.OpenAI.Azure.com/OpenAI/deployments/gpt35/chat/completions?API-version=2023-03-15-preview"
```

[Azure OpenAI 关于 API 版本、请求与返回的文档](https://learn.microsoft.com/en-us/Azure/cognitive-services/OpenAI/reference)  
[OpenAI 关于各 gpt 模型最大 tokens 数的文档](https://platform.OpenAI.com/docs/API-reference/completions/create#completions/create-max_tokens)

完成设置后，无需翻墙就可以在 VScode 中使用 ChatGPT Genie 了

# 高阶：部署基于 LLM 的聊天 bots

**_To be continued..._**

# Bonus Parts:

## 开发基于 LLMs 的应用

该部分以使用 OpenAI sdk 编写简单的脚本为例，介绍如何使用 OpenAI sdk 开发基于 LLMs 的应用

**_To be continued..._**

## GitHub 学生认证指南

**_To be continued..._**

## 用大陆 +86 手机号注册 Gmail

**_To be continued..._**
