# TangGo 测试平台
![TangGo头图.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709016785196-2242ab1b-08a1-404d-b4c2-097edf428c93.png#averageHue=%2331363b&clientId=ue6c850c5-14a0-4&from=paste&height=1080&id=fG7Sv&originHeight=1080&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=1711910&status=done&style=none&taskId=u29a273fb-6740-4019-abe9-b2a7e6221da&title=&width=1920)<br />
<p align="center" dir="auto">
  <img alt="Static Badge" src="https://img.shields.io/badge/%E4%BC%81%E4%B8%9A%E7%89%88-brightgreen?style=plastic&logo=%23FF3366&logoColor=%23FF3366&label=%E7%89%88%E6%9C%AC&color=%23FF3366">
  <img alt="Static Badge" src="https://img.shields.io/badge/%E4%B8%93%E4%B8%9A%E7%89%88-brightgreen?style=plastic&logo=%23FF3366&logoColor=%23FF3366&color=blue">
  <img alt="Static Badge" src="https://img.shields.io/badge/%E7%A4%BE%E5%8C%BA%E7%89%88-brightgreen?style=plastic&logo=%23FF3366&logoColor=%23FF3366&color=green">
</p>
<p align="center" dir="auto"><a href="https://tanggo.nosugar.tech/">官网</a> | <a href="https://nosugar.yuque.com/org-wiki-mrhite/tanggo">官方文档</a> </p>
<p align="center" dir="auto">语言选择： <a href="https://github.com/TangGolang/TangGo/blob/main/README_En.md">English</a> | <a href="https://github.com/TangGolang/TangGo/blob/main/README.md">中文</a></p>


<a name="uU7QA"></a>
# 概述
TangGo测试平台是无糖信息技术有限公司集多年渗透测试实战经验设计和开发的国产化综合性测试平台，为软件测试、网络安全从业人员提供强大且易用的测试工具及多人协同的工作环境，主要用于Web站点的功能测试、安全测试和安全评估。<br />● 集成了40多种**自研的跨平台**测试工具，支持**独立**和**界面**使用。<br />● 支持**团队协同测试**，测试数据动态推送、**实时同步**，支持以插件的形式兼容第三方工具。<br />● 支持界面和工具分离的**远程模式**部署，支持环境共享，**无缝切换办公场所**。<br />● 集成无代码可视化快速开发框架，**零编程**基础的用户也能够玩转安全测试开发。<br />● 基于**多年测试经验**开发，针对测试中的一些**难点和痛点**进行了优化。<br />![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709021155107-ff312fc9-5368-4495-b1a6-b6dec1a2f47a.png#averageHue=%23403f3e&clientId=u96555753-1eea-4&from=paste&height=1019&id=u20f8a61c&originHeight=1019&originWidth=1905&originalType=binary&ratio=1&rotation=0&showTitle=false&size=243706&status=done&style=none&taskId=u6425832a-89cc-43af-b28e-b95024e3877&title=&width=1905)

---

<a name="dm6VN"></a>
## 设计和组成
<a name="HdHaA"></a>
### 设计理念
TangGo 测试平台的设计秉承着**开放、扩展和定制**的理念。这些原则为开发者提供了灵活性和自由度，使他们能够根据具体需求定制和扩展TangGo框架，以适应不同的项目场景和业务需求。<br />![1](https://github.com/TangGolang/TangGo/assets/161299230/ee931e6c-c0e9-409b-8dad-6b28d8498334)

<a name="fAIPH"></a>
### 平台组成
TangGo 测试平台由跨平台工具集、跨平台用户界面、应用中心、远程服务平台、协同测试平台、可视化开发框架组成。

- **跨平台工具集**：Go编程语言开发的信息收集、漏洞扫描、漏洞测试、辅助工具等各类渗透测试中常用工具。跨平台、无依赖，使用方便、部署简单、性能高、兼容性强。
- **跨平台用户界面**：跨平台、简单易用的用户界面（各工具也可脱离界面独立使用），集成了自定义界面工具模块，可以轻松地给其他工具或脚本定制可视化的界面。
- **应用中心**：在线的官方应用平台。提供各类自研渗透测试工具的快速安装、更新和下载。第一时间获取最新应用、最新扫描规则数据以及使用说明文档。快速反馈工具的问题和建议。
- **远程服务平台**：一键部署的远程服务镜像，用户可在远程服务器上快速部署远程服务，让所有工具在远程服务器上工作，打造“云”式的工作环境。
- **协同测试平台**：搭载了协同测试平台客户端与服务端，通过协同测试平台，可节约数据传递、汇总和沟通协作的成本，提升测试效率，使测试过程更为清晰透明，也便于后期进行复盘。
- **可视化开发框架组成**：集成了无代码可视化快速开发框架，用户可以通过可视化界面的简单配置，快速定制各种测试流程，开发属于自己的跨平台测试工具。
<a name="O9N59"></a>
#### 跨平台工具集
TangGo提供了信息收集、弱点扫描、漏洞测试、测试辅助等测试过程所需的40多款常用工具，并且在持续扩充。<br />![2](https://github.com/TangGolang/TangGo/assets/161299230/d82d9b89-6484-4396-9256-b034e9b4eade)


<a name="UFZnA"></a>
#### 跨平台用户界面
TangGo提供了**跨平台**、简单易用的用户界面(各工具也可脱离界面独立使用)，界面下使用更加**舒适简便**。并且集成了**自定义界面**工具模块，可以轻松地给其他工具或脚本**定制可视化**的界面，将命令行工具转变为界面型工具，并可以对输出数据进行美化和解码，推送到**协同测试平台**。<br />![3](https://github.com/TangGolang/TangGo/assets/161299230/77af813b-2f19-46df-a4aa-44925d45e04d)

<a name="ycbbQ"></a>
#### 应用中心
TangGo的应用中心提供了**自行研发**且跨平台的各类渗透测试中的常用工具，并且在不断地扩充和更新。通过应用中心可**根据需要**，安装、更新、下载符合各平台需求的工具，也可以在上面反馈工具的问题和意见、建议。<br />![4](https://github.com/TangGolang/TangGo/assets/161299230/be1b34cd-9acb-4d41-afdc-7106ae725074)

<a name="IWsun"></a>
#### 协同测试平台
TangGo支持团队**协同测试**，搭载了协同测试平台和模块，实现了任务的管理、分配、跟进，团队和工具之间的**数据交互和数据共享**。节约了数据传递、汇总和人员沟通的**成本**，提升了**测试效率**，多维度的数据展示模式让测试流程更为清晰明朗，也便于后期进行**复盘**。

- 搭载协同测试平台，支持团队协作，协同测试
- 支持任务管理、成员管理、任务的分配、跟进、管控。
- 各工具可以通过协同平台客户端将数据推送到协同测试平台服务端
- 由协同测试平台服务端对数据进行清洗、分析和汇总、入库。
- 实时数据共享展示，支持多维度展示测试目标的各类数据，提供数据关系图、时序图等多种展示形式。
- 协同测试平台数据加密传输，支持内网部署，满足安全级别要求高的企业需求。
- 支持以插件的形式兼容第三方工具的数据推送与解析。

![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709007916412-42644c44-7c5b-4b58-a99e-252cfcc290ce.png#averageHue=%233a3b3b&clientId=uce93d22d-94b4-4&from=paste&height=367&id=ud104018e&originHeight=367&originWidth=1282&originalType=binary&ratio=1&rotation=0&showTitle=false&size=168628&status=done&style=none&taskId=ud7085997-da76-42a6-98e2-61fb1210def&title=&width=1282)
<a name="mGXxg"></a>
#### 远程服务平台
TangGo提供了可**一键部署**的远程服务平台，支持界面与工具分离的远程部署使用，实现分布式办公。办公场所无缝切换，长时间任务不中断，并且支持实现团队成员的**共享使用**，支持远程服务平台的**数据加密**推送到内网部署的协同测试平台服务端系统。<br />![5](https://github.com/TangGolang/TangGo/assets/161299230/8259f0ea-3a72-41cb-92a2-f4ebd143ff29)

<a name="GDR91"></a>
#### 无代码可视化快速开发框架
**无代码可视化开发框架**集成了常用和通用的测试流程，通过简单的界面配置即可实现测试流程的定制、衔接、调试、测试、执行和独立工具生成的框架。它能够将复杂的测试流程开发和调试简单化，**降低开发门槛**和成本，**缩短**开发周期，**提高**开发和测试**效率**。

- 通过**可视化界面**进行开发和调试，开发简单、流程清晰、调试简便，效率高。
- 内置多个通用的测试流程，如HTTP、TCP、UDP协议的测试、验证码识别、数据提取、数据处理以及无头浏览器的**自动化测试**流程。
- 支持自定义**全局变量和局部变量**，可与流程数据绑定，集成十多种数据处理规则，支持执行JS脚本及调用第三方工具处理数据，轻松实现各流程的顺畅衔接和数据处理、流转。
- 支持各流程及全流程的**可视化调试**和测试，调试和测试环节流程清晰透明，**易于**掌握各流程的工作情况、数据和变量变化。
- 无头浏览器的自动化测试流程支持**通信劫持**和断点劫持，支持智能断点，轻松实现浏览器加密数据的劫持、修改和发送、测试。
- 支持测试流程的导出以及**一键生成跨平台**的独立工具。

更多详情请点击：[无代码可视化快速开发框架](https://github.com/TangGolang/TangGo/blob/main/%E6%97%A0%E4%BB%A3%E7%A0%81%E5%8F%AF%E8%A7%86%E5%8C%96%E5%BF%AB%E9%80%9F%E5%BC%80%E5%8F%91%E6%A1%86%E6%9E%B6.md)
<a name="TS9Gc"></a>
## 功能特点

- **功能丰富**：包含信息收集、漏洞扫描、漏洞测试、辅助工具等四大类40多种渗透测试工具，仍然在不断地扩充和更新。除独立使用外还支持多人协同、远程部署的工作模式。
- **安全可靠**：框架内的所有工具均自行研发，从根本上避免了工具自身安全性的问题。平台框架及工具的数据均加密传输，协同平台服务端支持内网部署。
- **交互性强**：工具支持多种使用模式。搭载了协同测试平台，轻松实现数据共享，支持协同测试平台与工具的数据交互。
- **扩展性强**：搭建了无代码可视化开发框架，轻松实现各种场景的测试流程定制。主框架支持挂载自定义界面工具，支持自定义界面工具的输出推送到协同测试平台。
- **兼容性强**：跨平台，主框架和工具集均支持window、Linux、Mac等操作系统，一键安装、备份和更新。协同平台服务端支持内网部署，满足对安全级别要求高的企业要求。
- **可用性强**：长久更新升级维护，持续开发和更新，聆听用户的需求，改进升级，保持可用性和先进性。用户可通过应用中心第一时间获取最新版本。

![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709019998944-da337ff8-b682-4055-adf1-f595349018b8.png#averageHue=%237c7d7c&clientId=u60d92a21-cb0d-4&from=paste&height=648&id=u4083516a&originHeight=648&originWidth=1796&originalType=binary&ratio=1&rotation=0&showTitle=false&size=444990&status=done&style=none&taskId=u685a7c67-a3e7-4c20-8a7d-eba983e910c&title=&width=1796)

---

<a name="rshmM"></a>
## 下载和反馈

- 进入[**官网**](https://tanggo.nosugar.tech/)下载并安装
- 查看[**官方文档**](https://nosugar.yuque.com/org-wiki-mrhite/tanggo)学习使用
- 如果你有好的**建议**或者遇到**bug **和**其他问题**，欢迎使用 [**issue**](https://github.com/TangGolang/TangGo/issues) 提议。

---

<a name="hDD3c"></a>
## 公众号
![糖果底部-无糖码](https://github.com/TangGolang/TangGo/assets/161299230/c278ec71-6d15-457e-9f71-3d08e60a7f55)


<a name="tl60R"></a>
## 软件许可协议
**请您仔细阅读。本协议是您与我们（成都无糖信息技术有限公司，以下简称“无糖信息”）签定的软件许可协议。**<br />在使用我们（无糖信息）的软件（以下称许可软件）之前，请您仔细阅读本协议，特别是免除或者限制责任的条款、法律适用和争议解决条款。<br />无糖信息TangGo测试平台软件，以下称为“本软件”。<br />**重要提示：本《软件许可协议》（以下称为“本协议”）是您（自然人、法人或其他组织）与 我们（成都无糖信息技术有限公司）之间有关复制、下载、安装、购买、使用无糖信息软件以及任何相关材料（统一称作“软件”）及为该软件提供的任何更新（包括但不限于：错误修正程序、补丁程序、更新、升级、增强、新版软件和后续软件，这些内容统称为“更新”）和支持服务的法律协议。**<br />一旦您复制、下载、安装或者以其他方式使用本软件，即表明您完全同意并接受本协议各项条款，同时包括接受我们对协议各项条款随时所做的任何修改。如果您不同意本协议中的条款，请勿复制、下载、查看、安装或者以其他方式使用本软件。
<a name="zsMjr"></a>
### 1.软件许可：
在您完全接受并遵守本协议的基础上，本协议授予您使用本软件的某些权利和非独占性许可，允许您依据本协议各项条款许可的用途使用本软件，我们保留所有其他权利。<br />本协议中，将软件使用用途分为“个人非商业用途”和“商业用途”。<br />获得软件授权之后，您可以将本软件应用于“商业用途”，同时依据您所获得的授权服务类型中确定的技术支持期限、技术支持方式和技术支持内容获得指定范围内的技术支持服务。
<a name="wSo5I"></a>
### 2.试用版软件：
本软件可能提供试用版本，试用版软件仅用于在有限的期限内检查、演示和评估软件，其性能和兼容性均未能达到最终全面发布版本的级别，将来也存在对软件进行重大更改的可能，其仅供试用软件之用，请勿用于正式生产环境，也请勿泄漏于其他用户，如软件试用期间导致的软件程序泄漏，我司保留追究试用软件泄漏的权力。
<a name="TstRw"></a>
### 3.约束和限制：
（1）未获得本软件使用授权之前，您不得将本软件用于商业用途。<br />（2）无论如何，即无论用途如何、是否经过修改或美化、修改程度如何，只要使用本软件的整体或任何部分，未经我们官方书面授权许可，软件的版权标识禁止去除。<br />（3）我们提供的或您获得的有关本软件的任何信息只能由您为本协议许可的目的而使用，您不得透露给任何第三方；您不得创建任何与本软件风格基本相似的软件。<br />（4）对于从我们取得的任何信息、软件、产品或服务，您不得对其进行修改、改编、反编译、逆向工程、反汇编及绕过软件中的任何技术限制、或基于以上内容创建衍生作品、或以其他方式试图从本软件取得源代码、或重新包装本软件、或从软件文档中摘取其实质部分作其他应用。<br />（5）您不得对本软件以及与之关联的商业授权进行发布、出租、销售、分销、抵押、转让、许可或发放子许可证。
<a name="MBvZK"></a>
### 4.用户使用规则
请注意，使用本软件可能会涉及到法律和合规问题。您在使用本软件或服务时，不得将本软件产品或服务用于任何非法用途或本协议条款、条件和声明禁止的用途。您必须确保其使用符合所有相关的法律法规，包括但不限于数据隐私法规和网络安全法规等。如果您不确定您的使用是否合法，请在使用之前咨询法律专业人士。<br />4.1用户在使用本软件时必须符合中国有关法规以及其他有关国家和地区的法律规定以及国际法的有关规定。<br />4.2用户不得利用本软件从事以下危害计算机网络安全的活动，如果我们有理由认为用户的行为违反或可能违反下述规定的，我们可独立进行判断并处理，且有权在不事先通知的情况下终止向用户提供服务，并追究相关法律责任：<br />（1）未经允许，进入计算机信息网络或者使用计算机信息网络资源的；<br />（2）未经允许，对计算机信息网络功能进行删除、修改或者增加的；<br />（3）未经允许，对进入计算机信息网络中存储、处理或者传输的数据和应用程序进行删除、修改或者增加的；<br />（4）故意制作、传播计算机病毒等破坏性程序的；<br />（5）使用未经许可的数据或进入未经许可的服务器/账户；<br />（6）未经允许进入公众计算机网络或者他人计算机系统并删除、修改、增加存储信息；<br />（7）未经许可，企图探查、扫描、测试他人计算机软件系统或网络的弱点或其它实施破坏网络安全的行为；<br />（8）企图干涉、破坏他人计算机软件系统或网站的正常运行，故意传播恶意程序或病毒以及其他破坏干扰正常网络信息服务的行为；<br />（9）其他危害计算机信息网络安全的行为。<br />4.3用户须对自己在使用本软件服务过程中的行为承担法律责任。
<a name="TRoH9"></a>
### 5.免责说明：
（1）使用本软件可能存在风险，您必须自行承担其使用本软件的所有风险。<br />（2）使用本软件是基于您自己的判断和风险承受能力，并且您必须自行对其使用后果负责。<br />（3）在任何情况下，无论是因使用本软件或由于本软件引起的其他问题，我们不对您因使用本软件而导致的任何直接或间接损失负责，包括但不限于数据丢失，利润损失，业务中断等。<br />（4）任何对本软件的不当使用，包括但不限于非法入侵、攻击或破坏他人的系统或数据等行为，均由您自行承担法律责任。本软件不提供任何形式的保证。<br />（5）本软件不得用于非法的、未授权的或违反道德规范的活动。包括但不限于攻击、侵入、破解、欺骗、窃取信息或其他非法或恶意活动。我们不对您因使用本软件而导致的任何法律责任或其他责任承担任何责任，包括但不限于因违反法律法规而导致的责任。使用本软件的风险和责任由您自行承担。
<a name="oEUjh"></a>
### 6.权利和所有权的保留：
我们保留所有未在本协议中明确授予您的所有权利。我们保留随时更新本协议的权利，并只需公示于成都无糖信息技术有限公司官方网站，而无需征得您的事先同意且无需另行通知，更新后的内容应于公示即时生效。您可以随时访问无糖信息官方网站查阅最新版许可条款，在更新生效后您继续使用本软件则被视作您已接受了新的条款。
<a name="Bhwhv"></a>
### 7.知识产权
（1）本软件知识产权归我们独立所有。软件的结构、组织和代码以及与软件相关的所有信息内容为我们的保密信息。未经我们明确授权，您不得使用、复制、分发或修改本软件的任何组件。<br />（2）我们拥有许可软件的著作权、商业秘密以及其他相关的知识产权，包括与许可软件有关的各种文档资料。<br />（3）许可软件的相关标识属于我们及我们的关联公司的知识产权，并受到相关法律法规的保护。未经我们明确授权，您不得复制、模仿、使用或发布上述标识，也不得修改或删除应用产品中体现无糖信息及其关联公司的任何标识或身份信息。<br />（4）未经我们及我们的关联公司事先书面同意，您不得为任何营利性或非营利性的目的自行实施、利用、转让或许可任何第三方实施、利用、转让上述知识产权。
<a name="PsmKN"></a>
### 8.协议终止
（1）您应理解按授权范围使用许可软件、尊重软件及软件包含内容的知识产权、按规范使用软件、按本协议约定履行义务是您获取我们授权使用软件的前提，如您严重违反本协议，我们将终止使用许可。<br />（2）您一旦开始复制、下载、安装或者使用本软件，即被视为完全理解并接受本协议的各项条款，在享有上述条款授予的许可权力同时，也受到相关的约束和限制，本协议许可范围以外的行为，将直接违反本协议并构成侵权。<br />（3）一旦您违反本协议的条款，我们随时可能终止本协议、收回许可和授权，并要求您承担相应法律和经济责任。
<a name="EoiQs"></a>
### 9.其他
本协议的所有标题仅仅是为了醒目及阅读方便，本身并没有实际涵义，不能作为解释本协议涵义的依据。如果本协议中的任何条款被认定为无效或不可执行，该条款的无效性或不可执行性将不影响本协议的其他条款。<br />本协议受中华人民共和国法律管辖。若您在使用本软件期间发生任何纠纷或争议，首先应友好协商解决；协商不成的，您同意将纠纷或争议提交【成都仲裁委员会】仲裁解决。<br />成都无糖信息技术有限公司

---
