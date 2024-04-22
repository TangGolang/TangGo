![TangGo头图.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709016785196-2242ab1b-08a1-404d-b4c2-097edf428c93.png#averageHue=%2331363b&clientId=ue6c850c5-14a0-4&from=paste&height=1080&id=fG7Sv&originHeight=1080&originWidth=1920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=1711910&status=done&style=none&taskId=u29a273fb-6740-4019-abe9-b2a7e6221da&title=&width=1920)
<p align="center" dir="auto">
  <img alt="Static Badge" src="https://img.shields.io/badge/%E4%BC%81%E4%B8%9A%E7%89%88-brightgreen?style=plastic&logo=%23FF3366&logoColor=%23FF3366&label=%E7%89%88%E6%9C%AC&color=%23FF3366">
  <img alt="Static Badge" src="https://img.shields.io/badge/%E4%B8%93%E4%B8%9A%E7%89%88-brightgreen?style=plastic&logo=%23FF3366&logoColor=%23FF3366&color=blue">
  <img alt="Static Badge" src="https://img.shields.io/badge/%E7%A4%BE%E5%8C%BA%E7%89%88-brightgreen?style=plastic&logo=%23FF3366&logoColor=%23FF3366&color=green">
</p>
<p align="center" dir="auto"><a href="https://tanggo.nosugar.tech/">Official website</a> | <a href="https://nosugar.yuque.com/org-wiki-mrhite/tanggo">official documentation</a> </p>
<p align="center" dir="auto">Language selection： <a href="https://github.com/TangGolang/TangGo/blob/main/README_En.md">English</a> | <a href="https://github.com/TangGolang/TangGo/blob/main/README.md">中文</a></p>

<a name="uU7QA"></a>
# TangGo overview 
TangGo testing platform is a domestic comprehensive testing platform designed and developed by sugar-free Information Technology Co., Ltd. based on years of penetration testing experience. It provides powerful and easy-to-use testing tools and a collaborative working environment for software testing and network security practitioners. It is mainly used for functional testing, security testing and security assessment of Web sites. 

- integrates more than 40 types**self-developed cross-platform**test Tool, support**independent**and**interface**use. 
- support**team collaboration test**, test data dynamic push,**real-time synchronization**, supports compatibility with third-party tools in the form of plug-ins. 
- support interface and tool separation**remote mode**deployment, support environment sharing,**seamless office switching**. 
- integrate a code-free visual development framework**zero programming**basic users can also develop security tests. 
- based on**years of testing experience**development, aiming at some of the tests**difficulties and pain points**optimized.

![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709021155107-ff312fc9-5368-4495-b1a6-b6dec1a2f47a.png#averageHue=%23403f3e&clientId=u96555753-1eea-4&from=paste&height=1019&id=u20f8a61c&originHeight=1019&originWidth=1905&originalType=binary&ratio=1&rotation=0&showTitle=false&size=243706&status=done&style=none&taskId=u6425832a-89cc-43af-b28e-b95024e3877&title=&width=1905)

---

<a name="dm6VN"></a>
## Design and composition 
<a name="HdHaA"></a>
### design Concept 
the TangGo test platform is designed based on**open, expand, and customize**the concept. These principles provide developers with flexibility and freedom, enabling them to customize and expand the TangGo framework according to specific needs to adapt to different project scenarios and business needs.<br />![1](https://github.com/TangGolang/TangGo/assets/161299230/145a8993-17be-4dba-9e9d-13fd00aa29df)

<a name="fAIPH"></a>
### Platform composition 
the TangGo test platform consists of a cross-platform tool set, a cross-platform user interface, an application center, a remote service platform, a collaborative test platform, and a visual development framework. 

- **Cross-platform tool set**:common tools for penetration testing such as information collection, vulnerability scanning, vulnerability testing, and auxiliary tools developed by Go programming language. Cross-platform, independent, easy to use, easy to deploy, high performance, and strong compatibility. 
- **Cross-platform user interface**:cross-platform, easy-to-use user interface (each tool can also be used independently from the interface), integrated with custom interface tool modules, you can easily customize visual interfaces for other tools or scripts. 
- **Application Center**:the official online application platform. Provides quick installation, update, and download of various self-developed penetration testing tools. Obtain the latest application, scan rule data, and instructions immediately. Quickly feedback questions and suggestions from the tool. 
- **Remote service platform**:one-click deployment of remote service images allows you to quickly deploy remote services on remote servers, allowing all tools to work on remote servers, creating a "cloud" working environment. 
- **Collaborative Testing platform**:it is equipped with the client and server of the collaborative testing platform. Through the collaborative testing platform, the cost of data transmission, aggregation, communication and collaboration can be saved, the testing efficiency can be improved, the testing process can be clearer and more transparent, and it is also convenient for later review. 
- **Visual Development framework**:integrated with the code-free visual development framework, users can quickly customize various test processes and develop their own cross-platform test tools through simple configuration of the visual interface.
<a name="O9N59"></a>
#### Cross-platform tool set 
TangGo provides more than 40 commonly used tools for testing processes such as information collection, vulnerability scanning, vulnerability testing, and test assistance, and continues to expand. <br />![2](https://github.com/TangGolang/TangGo/assets/161299230/61cf8d3d-6e8c-4355-a533-fc343a81ae8e)

<a name="UFZnA"></a>
#### Cross-platform user interface 
TangGo provides **cross-platform**. Simple and easy-to-use user interface (each tool can also be used independently from the interface), which is more convenient to use under the interface**comfortable and simple**. And integrated**custom Interface**tool Module, which can be easily provided to other tools or scripts**custom visualization**the command line tool is transformed into an interface tool, and the output data can be beautified and decoded, and pushed**collaborative Testing Platform**.<br />![3](https://github.com/TangGolang/TangGo/assets/161299230/1242b2bf-6122-490b-ba11-0a4aba7bcc0e)

<a name="ycbbQ"></a>
#### Application Center 
tangGo's Application Center provides **self-developed** and cross-platform common tools in penetration testing, and constantly expand and update. Through the application center**as needed**, install, update, and download tools that meet the requirements of each platform. You can also feedback the questions, comments, and suggestions of the tools. <br />![4](https://github.com/TangGolang/TangGo/assets/161299230/27a64f33-7a91-49c8-b709-b05866ac1985)

<a name="IWsun"></a>
#### Collaborative Testing Platform 
TangGo support team **collaborative Testing**, equipped with collaborative testing platform and module, to achieve task management, allocation, follow-up, team and tools**data interaction and data sharing**. Saves data transmission, aggregation, and personnel communication.**Cost**, improved**test efficiency**, the multi-dimensional data display mode makes the test process clearer and clearer, which is also convenient for later development.**Double disk**. 

- It is equipped with a collaborative testing platform and supports teamwork and collaborative testing. 
- Supports task management, member management, task assignment, follow-up, and control. 
- Each tool can push data to the server of the collaborative testing platform through the client of the collaborative platform. 
- The server of the collaborative testing platform cleans, analyzes, summarizes, and stores data.
- Real-time data sharing display, supports multi-dimensional display of various types of data of test targets, and provides multiple display forms such as data relationship diagrams and timing diagrams. 
- The collaborative test platform supports encrypted data transmission and internal network deployment to meet the needs of enterprises with high security requirements. 
- Supports data push and parsing in the form of plug-ins compatible with third-party tools. 

![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709007916412-42644c44-7c5b-4b58-a99e-252cfcc290ce.png#averageHue=%233a3b3b&clientId=uce93d22d-94b4-4&from=paste&height=367&id=ud104018e&originHeight=367&originWidth=1282&originalType=binary&ratio=1&rotation=0&showTitle=false&size=168628&status=done&style=none&taskId=ud7085997-da76-42a6-98e2-61fb1210def&title=&width=1282)
<a name="mGXxg"></a>
#### Remote service platform 
TangGo provides**one-click deployment**the remote service platform supports remote deployment and use of interface and tool separation to realize distributed office. Seamless office switching, long-term tasks are not interrupted, and support team members**shared use**, support remote service platform**data encryption**push to the server system of the collaborative test platform deployed in the internal network. <br />![5](https://github.com/TangGolang/TangGo/assets/161299230/d31004d4-ded3-44f8-b842-f51e29634fc4)


<a name="GDR91"></a>
#### Quick development framework without code visualization 
**no code visual development framework**it integrates common and common test processes, and can realize the customization, connection, debugging, testing, execution and independent tool generation framework of the test process through simple interface configuration. It can simplify the development and debugging of complex testing processes,**lower the development threshold**and cost,**shorten**development cycle,**improve**development and testing**efficiency**. 

- Pass**Visual interface**for development and debugging, the development is simple, the process is clear, the debugging is simple, and the efficiency is high. 
- Built-in common testing processes, such as HTTP, TCP, UDP Protocol Testing, Verification code identification, data extraction, data processing, and headless browser**automated testing**process. 
- Supports customization**global and local variables?**, can be bound to process data, integrates more than ten data processing rules, supports executing JS scripts and calling third-party tools to process data, and easily realizes smooth connection, data processing and flow of various processes. 
- Supports all processes and the whole process**visual debugging**and the process of testing, debugging and testing is clear and transparent,**easy**master the working conditions, data and variable changes of each process. 
- Support for automated testing of headless browsers**communication hijacking**and supports intelligent breakpoints to easily hijack, modify, send, and test encrypted data in browsers. 
- Supports the export of test processes and**one-click generation cross-platform**the independent tool. 

For more information, click: [quick development framework without code visualization ](https://github.com/TangGolang/TangGo/blob/main/%E6%97%A0%E4%BB%A3%E7%A0%81%E5%8F%AF%E8%A7%86%E5%8C%96%E5%BF%AB%E9%80%9F%E5%BC%80%E5%8F%91%E6%A1%86%E6%9E%B6_En.md)
<a name="TS9Gc"></a>
## features 

- **features**:More than 40 penetration testing tools, including information collection, vulnerability scanning, vulnerability testing, and auxiliary tools, are constantly being expanded and updated. In addition to independent use, it also supports multi-person collaboration and remote deployment. 
- **Safe and reliable**:all tools in the framework are developed by themselves, which fundamentally avoids the security of the tools themselves. Data of the platform framework and tools are encrypted and transmitted, and the platform server supports internal network deployment. 
- **Strong interactivity**:the tool supports multiple usage modes. It is equipped with a collaborative testing platform to easily share data and support data interaction between the collaborative testing platform and tools. 
- **Strong scalability**:build a code-free visual development framework to easily customize test processes in various scenarios. The main framework supports mounting custom interface tools and pushing the output of custom interface tools to the collaborative testing platform. 
- **Strong compatibility**:cross-platform, the main framework and tool set support Windows, Linux, Mac and other operating systems, one-click installation, backup, and update. The server of the collaborative platform supports internal network deployment to meet the requirements of enterprises with high security levels. 
- **High availability**:update and maintain for a long time, continuously develop and update, listen to users' needs, improve and upgrade, and maintain availability and advancement. Users can obtain the latest version at the first time through the application center. 

![image.png](https://cdn.nlark.com/yuque/0/2024/png/39204304/1709019998944-da337ff8-b682-4055-adf1-f595349018b8.png#averageHue=%237c7d7c&clientId=u60d92a21-cb0d-4&from=paste&height=648&id=u4083516a&originHeight=648&originWidth=1796&originalType=binary&ratio=1&rotation=0&showTitle=false&size=444990&status=done&style=none&taskId=u685a7c67-a3e7-4c20-8a7d-eba983e910c&title=&width=1796)

---

<a name="rshmM"></a>
## Download and feedback 

- enter [**official website**](https://tanggo.nosugar.tech/)download and Install 
- view [**official documentation**](https://nosugar.yuque.com/org-wiki-mrhite/tanggo)learning and using
- If you have good**suggestion**or encounter**bug**and**other questions**, welcome to use**issue**proposal. 

---

<a name="hDD3c"></a>
## Official account
![糖果底部-无糖码](https://github.com/TangGolang/TangGo/assets/161299230/7fdc1a25-950f-4f22-826f-1dbe60a77fa0)


<a name="tl60R"></a>
## Software License Agreement 
**please read carefully. This agreement is a software license agreement signed between you and us (Chengdu sugar-free Information Technology Co., Ltd., hereinafter referred to as "sugar-free information").** <br />Before using our (sugar-free information) software (hereinafter referred to as licensed software), please read this agreement carefully, especially the terms of exemption or limitation of liability, application of law and dispute resolution. <br />Sugar-free information TangGo test platform software, hereinafter referred to as "this software". <br />**Important note: This software license agreement (hereinafter referred to as "this agreement") refers to the copy, download, installation, purchase and use of sugar-free information software and any related materials (collectively referred to as "software") between you (natural person, legal person or other organization) and US (Chengdu sugar-free Information Technology Co., Ltd) and any updates (including but not limited to: Error correction procedures, patches, updates, upgrades, enhancements, new versions of software and subsequent software, collectively referred to as "updates") and legal agreements to support services.**<br />Once you copy, download, install or otherwise use the software, it means that you fully agree to and accept the terms of this agreement, including any changes we make to the terms of this agreement at any time. If you do not agree to the terms of this agreement, do not copy, download, view, install or otherwise use the software. 
<a name="BO6y6"></a>
### 1. Software license:
On the basis of your full acceptance and compliance with this agreement, this agreement grants you certain rights and non-exclusive licenses to use this software, and allows you to use this software for purposes permitted in accordance with the terms of this agreement. We reserve all other rights. <br />In this agreement, the use of software is divided into "personal non-commercial use" and "commercial use". <br />After obtaining the software authorization, you can apply the software to "commercial use" and obtain technical support services within the specified range according to the technical support period, technical support methods and technical support content specified in the authorized service type you have obtained. 
<a name="Hsa04"></a>
### 2. Trial software: 
this software may provide a trial version. The trial version is only used to check, demonstrate and evaluate the software within a limited period of time. Its performance and compatibility fail to reach the level of the final full release version. There may be major changes to the software in the future. It is only used for trial software. Please do not use it in a formal production environment or leak it to other users, such as software program leakage caused during the trial period, our company reserves the right to investigate the leakage of trial software.
<a name="uWPlq"></a>
### 3. Constraints and restrictions: 
(1) You shall not use the software for commercial purposes before obtaining the license to use the software. <br />(2) In any case, that is, regardless of the purpose, whether it has been modified or beautified, and the degree of modification, as long as the whole or any part of the software is used, the copyright mark of the software is prohibited from being removed without our official written permission. <br />(3) any information we provide or you obtain about this software can only be used by you for the purposes permitted by this agreement, and you shall not disclose it to any third party; You shall not create any software that is basically similar to the style of this software. <br />(4) for any information, software, products or services obtained from us, you shall not modify, adapt, decompile, reverse engineer, disassemble or bypass any technical restrictions in the software, or create derivative works based on the above contents, or otherwise attempt to obtain source code from the software, or repackage the software, or extract the essence from the software documents for other applications. <br />(5) You shall not issue, lease, sell, distribute, mortgage, transfer, license or issue sub-licenses to the software and its related commercial licenses. 
<a name="vCboS"></a>
### 4. User usage rules 
please note that using this software may involve legal and compliance issues. When you use this software or service, you shall not use this software product or service for any illegal use or for any use prohibited by the terms, conditions and declarations of this agreement. You must ensure that its use complies with all relevant laws and regulations, including but not limited to data privacy regulations and cyber security regulations. If you are not sure whether your use is legal, please consult a legal professional before using it. <br />4.1 when using this software, users must comply with relevant Chinese laws and regulations, legal provisions of other relevant countries and regions, and relevant provisions of international law.<br />4.2 users shall not use this software to engage in the following activities that endanger computer network security. If we have reasons to believe that the user's behavior violates OR may violate the following provisions, we can judge and deal with it independently, and have the right to terminate the provision of services to users without prior notice and pursue relevant legal responsibilities: <br />(1) entering the computer information network or using computer information network resources without permission; <br />(2) deleting, modifying or adding computer information network functions without permission; <br />(3) deleting, modifying or adding data and applications stored, processed or transmitted in the computer information network without permission; <br />(4) deliberately making and spreading destructive programs such as computer viruses; <br />(5) use unauthorized data or enter unauthorized servers/accounts; <br />(6) entering the public computer network or other people's computer system without permission and deleting, modifying and adding stored information; <br />(7) attempting to detect, scan and test the weaknesses of other people's computer software systems or networks or other acts that undermine network security without permission; <br />(8) attempting to interfere with or destroy the normal operation of other people's computer software systems or websites, deliberately spreading malicious programs or viruses, and other acts that undermine and interfere with normal network information services; <br />(9) other behaviors that endanger the security of computer information network. <br />4.3 Users shall bear legal responsibility for their actions in the process of using the software services.
<a name="p2SEp"></a>
### 5. Disclaimer: 
(1) there may be risks in using this software, and you must bear all risks in using this software. <br />(2) the use of this software is based on your own judgment and risk tolerance, and you must be responsible for the consequences of its use. <br />(3) under any circumstances, whether due to the use of this software or other problems caused by this software, we are not responsible for any direct or indirect losses caused by your use of this software, including but not limited to data loss, profit loss, business interruption, etc. <br />(4) You shall be liable for any improper use of the software, including but not limited to illegal invasion, attack or destruction of other people's systems or data. This software does not provide any form of warranty. <br />(5) This software shall not be used for illegal, unauthorized or ethical activities. Including but not limited to attacks, intrusions, cracking, cheating, information theft, or other illegal or malicious activities. We do not assume any liability for any legal liability or other liability arising from your use of the software, including but not limited to liability arising from violation of laws and regulations. The risks and responsibilities of using this software shall be borne by you. 
<a name="ZQlfo"></a>
### 6. Retention of rights and ownership: 
we reserve all rights not expressly granted to you in this agreement. We reserve the right to update this agreement at any time and only need to publicize it on the official website of Chengdu sugar-free Information Technology Co., Ltd. without your prior consent and without further notice. The updated content shall take effect immediately upon publicity. You can visit the sugar-free information official website at any time to check the latest version of the license terms. If you continue to use the software after the update takes effect, you will be deemed to have accepted the new terms. 
<a name="HvGKH"></a>
### 7. Intellectual property rights
(1) the intellectual property rights of this software are independently owned by us. The structure, organization and code of the software and all information related to the software are our confidential information. You shall not use, copy, distribute, or modify any components of the software without our explicit authorization. <br />(2) we have the copyright, trade secrets and other relevant intellectual property rights of licensed software, including various documents related to licensed software. <br />(3) the relevant identification of the licensed software belongs to the intellectual property rights of us and our affiliates and is protected by relevant laws and regulations. Without our explicit authorization, you shall not copy, imitate, use or publish the above identification, nor modify or delete any identification or identity information that reflects sugar-free information and its affiliates in your application. <br />(4) without the prior written consent of us and our affiliates, you shall not implement, utilize, transfer, or implement, utilize, or transfer the above intellectual property rights by any third party for any profit or non-profit purpose.
<a name="grYr6"></a>
### 8. Termination of the agreement 
(1) you shall understand that the use of licensed software in accordance with the scope of authorization, respect for the intellectual property rights of the software and its contents, use the software in accordance with regulations, and perform obligations in accordance with the provisions of this agreement are the prerequisites for you to obtain our authorization to use the software. If you seriously violate this agreement, we will terminate the license. <br />(2) once you begin to copy, download, install or use this software, you will be deemed to fully understand and accept the terms of this agreement. While enjoying the licensing rights granted by the above terms, you will also be subject to relevant restrictions and restrictions. Any act beyond the scope of this agreement will directly violate this agreement and constitute infringement. <br />(3) Once you violate the terms of this agreement, we may terminate this agreement, withdraw the license and authorization at any time, and require you to assume corresponding legal and economic responsibilities. 
<a name="k0e4r"></a>
### 9. Others 
all titles of this agreement are only for the purpose of being eye-catching and convenient to read. They have no actual meaning and cannot be used as the basis for explaining the meaning of this agreement. If any provision of this agreement is deemed invalid or unenforceable, the invalidity or non-enforceability of such provision will not affect other provisions of this agreement. <br />This agreement is governed by the laws of the People's Republic of China. If any dispute or dispute occurs during your use of the software, it shall be settled through friendly negotiation first. If negotiation fails, you agree to submit the dispute or dispute to **[Chengdu Arbitration Commission]** for arbitration. <br />Chengdu sugar-free Information Technology Co., Ltd.

---


