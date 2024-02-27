# TangGo 测试平台
![TangGo头图.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709016785196-2242ab1b-08a1-404d-b4c2-097edf428c93.png#averageHue=%2331363b&clientId=ue6c850c5-14a0-4&from=paste&height=1080&id=fG7Sv&originHeight=1080&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=1711910&status=done&style=none&taskId=u29a273fb-6740-4019-abe9-b2a7e6221da&title=&width=1920)<br />
<p align="center" dir="auto">
  <img alt="Static Badge" src="https://img.shields.io/badge/%E4%BC%81%E4%B8%9A%E7%89%88-brightgreen?style=plastic&logo=%23FF3366&logoColor=%23FF3366&label=%E7%89%88%E6%9C%AC&color=%23FF3366">
  <img alt="Static Badge" src="https://img.shields.io/badge/%E4%B8%93%E4%B8%9A%E7%89%88-brightgreen?style=plastic&logo=%23FF3366&logoColor=%23FF3366&color=blue">
  <img alt="Static Badge" src="https://img.shields.io/badge/%E7%A4%BE%E5%8C%BA%E7%89%88-brightgreen?style=plastic&logo=%23FF3366&logoColor=%23FF3366&color=green">
</p>
<p align="center" dir="auto"><a href="https://tanggo.nosugar.tech/">官网</a> | <a href="https://nosugar.yuque.com/org-wiki-mrhite/tanggo">官方文档</a> </p>
<p align="center" dir="auto">语言选择： <a href="https://github.com/TangGolang/TangGo/blob/main/README.md">English</a> | <a href="https://github.com/TangGolang/TangGo/blob/main/README.md">中文</a></p>


<a name="uU7QA"></a>
# 概述
TangGo测试平台是无糖信息技术有限公司集多年渗透测试实战经验设计和开发的国产化综合性测试平台，为软件测试、网络安全从业人员提供强大且易用的测试工具及多人协同的工作环境，主要用于Web站点的功能测试、安全测试和安全评估。<br />● 集成了40多种**自研的跨平台**测试工具，支持**独立**和**界面**使用。<br />● 支持**团队协同测试**，测试数据动态推送、**实时同步**，支持以插件的形式兼容第三方工具。<br />● 支持界面和工具分离的**远程模式**部署，支持环境共享，**无缝切换办公场所**。<br />● 集成无代码可视化快速开发框架，**零编程**基础的用户也能够玩转安全测试开发。<br />● 基于**多年测试经验**开发，针对测试中的一些**难点和痛点**进行了优化。<br />![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709021155107-ff312fc9-5368-4495-b1a6-b6dec1a2f47a.png#averageHue=%23403f3e&clientId=u96555753-1eea-4&from=paste&height=1019&id=u20f8a61c&originHeight=1019&originWidth=1905&originalType=binary&ratio=1&rotation=0&showTitle=false&size=243706&status=done&style=none&taskId=u6425832a-89cc-43af-b28e-b95024e3877&title=&width=1905)

---

<a name="dm6VN"></a>
## 设计和组成
<a name="HdHaA"></a>
### 设计理念
TangGo 测试平台的设计秉承着**开放、扩展和定制**的理念。这些原则为开发者提供了灵活性和自由度，使他们能够根据具体需求定制和扩展TangGo框架，以适应不同的项目场景和业务需求。<br />![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1708938902604-2012f835-1a3e-420a-b9c6-2b7d3b0c4ffe.png#averageHue=%232f343f&clientId=ud01826cc-c5bd-4&from=paste&height=475&id=u9545198c&originHeight=475&originWidth=1391&originalType=binary&ratio=1&rotation=0&showTitle=false&size=106671&status=done&style=none&taskId=u7c5c94ef-7d3d-4345-af36-328533b03e2&title=&width=1391)
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
TangGo提供了信息收集、弱点扫描、漏洞测试、测试辅助等测试过程所需的40多款常用工具，并且在持续扩充。<br />![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709014839674-275bad2d-55db-4972-b47e-4540d12b83cb.png#averageHue=%235a4c37&clientId=uce93d22d-94b4-4&from=paste&height=335&id=u983b5444&originHeight=335&originWidth=1346&originalType=binary&ratio=1&rotation=0&showTitle=false&size=105905&status=done&style=none&taskId=u6014add5-a2bf-4df4-8921-b27d5f5e544&title=&width=1346)
<a name="UFZnA"></a>
#### 跨平台用户界面
TangGo提供了**跨平台**、简单易用的用户界面(各工具也可脱离界面独立使用)，界面下使用更加**舒适简便**。并且集成了**自定义界面**工具模块，可以轻松地给其他工具或脚本**定制可视化**的界面，将命令行工具转变为界面型工具，并可以对输出数据进行美化和解码，推送到**协同测试平台**。<br />![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709015426884-bd606a20-97e2-4f12-9371-b0935976efcb.png#averageHue=%232f2c27&clientId=uce93d22d-94b4-4&from=paste&height=535&id=ua8a74248&originHeight=535&originWidth=1380&originalType=binary&ratio=1&rotation=0&showTitle=false&size=159185&status=done&style=none&taskId=u43e8f387-6575-466a-a8a2-a96f8157715&title=&width=1380)
<a name="ycbbQ"></a>
#### 应用中心
TangGo的应用中心提供了**自行研发**且跨平台的各类渗透测试中的常用工具，并且在不断地扩充和更新。通过应用中心可**根据需要**，安装、更新、下载符合各平台需求的工具，也可以在上面反馈工具的问题和意见、建议。<br />![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709015452510-911d5faa-2d36-4f53-89cb-309aae9ed703.png#averageHue=%2328251f&clientId=uce93d22d-94b4-4&from=paste&height=525&id=u08f0a84c&originHeight=525&originWidth=1394&originalType=binary&ratio=1&rotation=0&showTitle=false&size=169092&status=done&style=none&taskId=u63c81c7f-6930-4892-907b-663e5f28cc8&title=&width=1394)
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
TangGo提供了可**一键部署**的远程服务平台，支持界面与工具分离的远程部署使用，实现分布式办公。办公场所无缝切换，长时间任务不中断，并且支持实现团队成员的**共享使用**，支持远程服务平台的**数据加密**推送到内网部署的协同测试平台服务端系统。<br />![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709013915479-c63757aa-9f9c-4be8-b951-714403c4fd34.png#averageHue=%231b1b1a&clientId=uce93d22d-94b4-4&from=paste&height=728&id=u99f0b5fd&originHeight=728&originWidth=1914&originalType=binary&ratio=1&rotation=0&showTitle=false&size=587985&status=done&style=none&taskId=u7ecad568-20e0-4328-9358-c9812f8bf2b&title=&width=1914)
<a name="GDR91"></a>
#### 无代码可视化快速开发框架
**无代码可视化开发框架**集成了常用和通用的测试流程，通过简单的界面配置即可实现测试流程的定制、衔接、调试、测试、执行和独立工具生成的框架。它能够将复杂的测试流程开发和调试简单化，**降低开发门槛**和成本，**缩短**开发周期，**提高**开发和测试**效率**。

- 通过**可视化界面**进行开发和调试，开发简单、流程清晰、调试简便，效率高。
- 内置多个通用的测试流程，如HTTP、TCP、UDP协议的测试、验证码识别、数据提取、数据处理以及无头浏览器的**自动化测试**流程。
- 支持自定义**全局变量和局部变量**，可与流程数据绑定，集成十多种数据处理规则，支持执行JS脚本及调用第三方工具处理数据，轻松实现各流程的顺畅衔接和数据处理、流转。
- 支持各流程及全流程的**可视化调试**和测试，调试和测试环节流程清晰透明，**易于**掌握各流程的工作情况、数据和变量变化。
- 无头浏览器的自动化测试流程支持**通信劫持**和断点劫持，支持智能断点，轻松实现浏览器加密数据的劫持、修改和发送、测试。
- 支持测试流程的导出以及**一键生成跨平台**的独立工具。

更多详情请点击：[无代码可视化快速开发框架]()
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
- 如果你有好的**建议**或者遇到**bug **和**其他问题**，欢迎使用 [**issue**](https://github.com/TangGolang/TangGo/issues) 提议，也欢迎加入**社区反馈**。

---

<a name="hDD3c"></a>
## 加入社区
通过微信交流群反馈：关注【无糖反网络犯罪研究中心】公众号，回复“TangGo”，加入交流群进行反馈。<br />![23360031363_132133311803_TangGO底图.gif](https://cdn.nlark.com/yuque/0/2024/gif/39204304/1709005519414-ff34c98d-2a31-4fa4-a42b-bd2fa600ebd6.gif#averageHue=%2326292c&clientId=u156eeb4b-dbd9-4&from=paste&height=517&id=u81f31663&originHeight=517&originWidth=1481&originalType=binary&ratio=1&rotation=0&showTitle=false&size=2717835&status=done&style=none&taskId=uff78440b-918b-4a15-b621-f5e4f8482ad&title=&width=1481)
<a name="tl60R"></a>
## 免责声明
使用 TangGo 测试平台（以下简称“软件”）之前，请务必仔细阅读本免责声明。通过下载、安装或使用本软件，您表示已理解并接受本免责声明的所有条款和条件。

1. **风险自负**：您明确了解并同意，网络安全领域存在不断变化的风险和威胁。尽管本软件旨在提供网络安全功能和保护，但我们无法保证其能够完全防止所有安全漏洞、攻击或数据泄露。您使用本软件的风险自负，我们不对因使用或无法使用本软件而导致的任何直接或间接损失承担责任。
2. **软件功能**：本软件提供的功能和特性可能会根据我们的更新和改进而发生变化。我们保留在不事先通知的情况下添加、修改或删除软件功能的权利。您有责任定期检查和更新软件，以确保您使用的是最新版本。
3. **第三方组件**：本软件可能包含第三方提供的组件、库或代码。尽管我们尽力确保这些组件的安全性和稳定性，但我们无法对其性能和安全性提供任何保证。您应自行评估和决定是否信任这些第三方组件。
4. **法律责任限制**：在法律允许的范围内，我们不对因使用或无法使用本软件而产生的任何特殊、偶然、间接或后果性损失承担赔偿责任，包括但不限于数据丢失、利润损失或业务中断等。
5. **使用限制**：您同意仅将本软件用于合法和道德上可接受的目的，并遵守所有适用的法律和法规。您不得利用本软件进行任何非法活动，包括但不限于网络攻击、未经授权的访问或数据窃取等。
6. **许可和知识产权**：本软件受版权、商标和其他知识产权法律的保护。您仅获得有限的、非排他性的、不可转让的许可证来使用本软件。您不得复制、修改、分发、出租、租赁或出售本软件的任何部分，除非获得我们的明确书面许可。
7. **无担保**：本软件按“现状”提供，不提供任何明示或暗示的担保，包括但不限于适销性、特定用途的适用性或非侵权性的担保。我们不对软件的性能、可靠性或持续性提供任何保证。

通过使用本软件，您明确同意上述免责声明的所有条款和条件。如果您不同意这些条款，请勿下载、安装或使用本软件。

---
