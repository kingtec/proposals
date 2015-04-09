---
layout: proposal
title: "金特集团IT系统内部审核及改组方案"
date: 2015-03-26 10:00:00
author: 何卡罗
categories: proposals
---

现在集团的IT系统机构存在着问题，迟早需要结局，以下为集团的目前IT机构形式的简报，IT机构内部审核报告以及重组与改善集团IT机构的方案。

---


## 目录

1. [金特集团IT形式]
	1. [IT形式问题简介]
	2. [IT形式问题解释图]
2. [硬件审核及更新方案]
	1. [硬件审核结果]
	2. [硬件组织结构重组方案]
	3. [IT组织机构重组后结果]
3. [软件审核及更新方案]
	1. [用友U8财务管理软件升级方案]
	2. [OA流程审批系统升级方案]
4. [预算]
	1. [公司目前IT年开支]
	2. [公司IT组织机构重组更新活动预算]
	3. [公司IT重组更新后预计年开支]
5. [结论]
{: .tab-contents}

[金特集团IT形式]: #one
[IT形式问题简介]: #one-one
[IT形式问题解释图]: #one-two
[硬件审核及更新方案]: #two
[硬件审核结果]: #two-one
[硬件组织结构重组方案]: #two-two
[IT组织机构重组后结果]: #two-three
[软件审核及更新方案]: #three
[用友U8财务管理软件升级方案]: #three-one
[OA流程审批系统升级方案]: #three-two

<!-- [官网]: #three-three -->

[预算]: #four
[公司目前IT年开支]: #four-one
[公司IT组织机构重组更新活动预算]: #four-two
[公司IT重组更新后预计年开支]: #four-three
[结论]: #five


---

## 一. 金特集团IT形式
{: #one}

我公司IT形式最大问题如下：


1. 服务器硬件管理杂乱
2. 服务器硬件和操作系统落后
3. OA历程审批系统落后
4. 财务管理软件落后
5. 太多第三方的参与


这些问题对我公司的负效应可从以下图解中看出：


### IT目前结构形式图
{: #one-two}

<!-- <img class="img-responsive" src="/img/金特IT情况.svg"> -->
![金特IT目前组织机构](/img/金特IT情况.svg){: .img-responsive}

---

## 二. 硬件审核及更新方案
{: #two}

### 1. 硬件审核结果
{: #two-one}

如上面的图所示，我公司在临汾路的办事处和浦东沈家弄的机房都有服务器。 这并不是最理想的情况，因为：

- 这种非集中性的形式在管理的方面上会带来很多不便。 
- 临汾路办公室的互联网环境不妙（作为居民区很难满足企业的条件，稳定性不高）。
- 沈家弄的机房算是下层的机房，安全性很弱 （我好次几叫他们重启服务器，也没有人确认过我的身份）。

既然如此， 为了将我公司整个IT组织机构改制为更有组织性，更有集中控制性的组织机构，我公司面临两种选择：

1. 将所有服务器都放在某一家下属公司的管辖下，或
2. 将所有服务器托管给专业的机房

由于我公司在临汾路办事处和沈家弄机房的两台服务器是全集团用的服务器，到底将它们方放在什么地方需要进行仔细考虑。如果将两台服务器放在自己下属公司的管辖下，那么公司可以节省专业机房的托管费，但是考虑到公司目前状况，我不建议这样做，因为：

- 实际上我公司只有临汾路办事处和齐力公司两个地方可放服务器。
- 如上所述，临汾路的互联网环境不妙。
- 由于新疆很严格的互联网管制, 外地用户易遭遇服务中断。
- 服务器所放的办事处必须配企业网络套餐，配固定IP地址， 成本很高。


最有力的论据反对这项措施就是上面所述的最后原因。 为了让外地用户远程接入临汾路办事处的服务器来操作财务任务，上海才云需要承担每年30,000元的企业网络套餐的费用以供固定IP地址。如果将临汾路的服务器也托管出去，换民用网络套餐， 我公司每年便可以节约20,000多元的开支。 

既然如此，第二种选择似乎更为合理。我公司的OA审批流程及管网的服务器已托管给第三方的服务器托管公司，硬件在中国电信浦东沈家侬的数据中心，价格为6,800远一年, 而且如上所述，沈家弄数据中心算比较低档，设备过时， 安全性较弱。 如果把临汾路办事处的财务服务器托管给第三方的服务器托管公司， 放在沈家弄数据中心，那每年的托管费为13,600元一年。 如果把临汾的财务服务器和已经托管出去的OA系统和管网的服务器一起搬到好一点的数据中心，那么每年的托管费为8,000元以上一年一台，一共为16,000元以上一年。 

我公司快单位服务器的需求只限于两台服务而已，所以16,000元一年的费用偏高, 而且这还不包括硬件更新的费用。 

鉴于以上所述的论据反对公司内部服务器管理方式， 并且考虑到对外托管服务器硬件方式的费用之高，我建议第三种方案：**云服务器托管**


### 2. 硬件组织结构重组方案
{: #two-two}

#### 云服务器： 省钱 + 省麻烦

云服务器是未来。互联网企业（例如阿里巴巴）的服务器不计其数，因此它们可以把大规模效应带来的经济节约传给最终客户。这种新的形势使企业能够将硬件管理，软件管理，以及安全忧虑都外包出去。 因为云服务是虚拟服务器, 不依赖于底层的硬体， 所以可以随时调整配置 （比如随时调内存，硬盘内存，CPU核的数量，系统版本， 宽带网速等），使企业能够跟着自己的需求瞬间扩充或缩小容量， 也就是赋予公司很高的灵活性。 

云服务器的另外一个优势在于它的定价体系，如"随意点菜”， 包月制等定价方案， 也就是说客户能够只按照自己的配置需求，容量需求和时间需求而购买。无论从哪个方面来看， 云服务器比传统服务器托管更加有效和优惠。 

以下可了解阿里云平台上租约两台服务器的报价：

阿里云Linux服务器（OA系统 + 公司网站） 

<!-- <img class="img-responsive" src="/img/aliyun1.png"> -->
![金特IT目前组织机构](/img/aliyun1.png){: .img-responsive}

阿里云Windows服务器（用友U8财务软件） 

<!-- <img class="img-responsive" src="/img/aliyun2.png"> -->
![金特IT目前组织机构](/img/aliyun2.png){: .img-responsive}

<!-- ### 硬件操作系统更新方案

<div class="table-responsive">
	<table class="table table-hover table-bordered">
	  <thead>
	    <tr>
	      <th>#</th>
	      <th>硬件</th>
	      <th>处理器（CPU）</th>
	      <th>内存（RAM）</th>
	      <th>用途</th>
	      <th>系统</th>
	      <th>地点</th>
	      <th>状态</th>
	    </tr>
	  </thead>
	  <tbody>
	    <tr>
	      <th scope="row">1</th>
	      <th>联想主机（转变为服务器）</th>
	      <th>2核</th>
	      <th>1GB</th>
	      <th>火墙，宽带流量控制</th>
	      <th>Windows 2003 服务器系统</th>
	      <th>上海临汾路1368号</th>
	      <th>加一条内存,把系统升级到Windows2008年,便可</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>联想转用服务器</th>
	      <th>2核</th>
	      <th>4GB</th>
	      <th>财务服务器（用友U8财务软件）整个集团都在用</th>
	      <th>Windows 2003 服务器系统</th>
	      <th>上海临汾路1368号</th>
	      <th class="">建议换云服务器替代此角色，也就是统升级到windows2012年版本, 把CPU升级到4核CPU, 加4GB的内存。</th>
	    </tr>
	    <tr>
	      <th scope="row">3</th>
	      <th>联想主机（转变为服务器）</th>
	      <th>2核</th>
	      <th>2GB</th>
	      <th>钢贸软件</th>
	      <th>Windows 2003 服务器系统</th>
	      <th>上海临汾路1368号</th>
	      <th class="info">目前无人用，建议改换用途</th>
	    </tr>
	    <tr>
	      <th scope="row">4</th>
	      <th>联想主机（转变为服务器）</th>
	      <th>2核</th>
	      <th>2GB</th>
	      <th>OA系统， 公司官网</th>
	      <th>Windows 2003 服务器系统</th>
	      <th>上海电信沈家弄机房（沈家弄路650号）</th>
	      <th>换Linux服务器, 装上NGINX http 网服务器 （官网）, 装tomcat java 服务器 （OA 系统）</th>
	    </tr>
	  </tbody>
	</table>
</div> -->

<!-- 
目前我公司的服务器全都装了Windows2003年服务器系统。这款系统不但很老，微软也已经宣布从2015年7月14日将停止对这款系统的支持。虽然这款系统到时候依然能够运行，但是失去了微软提供的安全更新，服务器就会成为黑客的靶子。 我公司最好采取升级系统的措施。
 -->

### 3. IT组织机构重组后结果
{: #two-three}


若果我公司采取此报告所建议的措施，结果会是更简化，更为容易管理，营运成本更低的IT组织机构。预期结果可从以下图解中看出：

<!-- <img class="img-responsive" src="/img/金特IT理想情况2.svg"> -->
![金特IT目前组织机构](/img/金特IT理想情况2.svg){: .img-responsive}


---


## 三. 软件审核及更新方案
{: #three}

目前在全公司部署有以下软件：

<div class="table-responsive">
	<table class="table table-hover table-bordered">
	  <thead>
	    <tr>
	      <th>#</th>
	      <th>软件</th>
	      <th>用途</th>
	      <th>状态</th>
	      <th>运营成本</th>
	    </tr>
	  </thead>
	  <tbody>
	    <tr>
	      <th scope="row">1</th>
	      <th>用友U8财务软件，980版本（2008年）</th>
	      <th>基本财务管理软件</th>
	      <th>整个集团正在用。此版本很老，<br>建议更新到最新版本。每年得交服务费</th>
	      <th>8,600远年服务费</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>科迈RAS远程软件。</th>
	      <th>虚拟局域连接软件，<br>使能够外雇员能够安全地连接到财务服务器</th>
	      <th>到现在没什么大的问题，不过稳定性不高，<br>外地会计偶尔会遇到打印不了凭证的故障。</th>
	      <th>6,000年服务费</th>
	    </tr>
	    <tr>
	      <th scope="row">3</th>
	      <th>网易企业邮箱</th>
	      <th>集团@kingtec.cc的企业邮箱服务</th>
	      <th>到目前为止对此服务十分满意。优质产品。</th>
	      <th>一次性费用 （30,000元），年运营成本为0</th>
	    </tr>
	    <tr>
	      <th scope="row">4</th>
	      <th>OA系统</th>
	      <th>办公平台，审批流程，考核</th>
	      <th>只支持IE8.0以下版本的浏览器，<br>不支持移动设备的浏览器, 用户界面过时，<br>调整流程的过程极复杂，各个方面不足。</th>
	      <th>一次性费用，年运营成本为0</th>
	    </tr>
	  </tbody>
	</table>
</div>


### 1. 用友U8平台升级
{: #three-one}

目前我公司的财务服务器装了用友U8财务平台9.80版本，此版本于2008年上市，总算是比较老的版本。 
此版有以下缺点：

- 缺少最基本的财务分析功能。
- 每年的帐套结转必须得手工操作，易于犯错误。 
- 用户界面过时，很多新来的会计于出纳已习惯使用更新的版本。 
- 虚拟局域网远程应用程序（就是让外地财务人员能够从上海办事处内网之外连接到财务服务器操作财务任务）最近表现得很不稳定，尤其导致了，并且因为此应用程序由第三方提供，从而使难以协调资源管理和技术支持 （财务人员遭遇问题时常不知道到底和谁联系）。

为解决此问题，我建议我公司立即将用友U8财务管理软件升级到最新的版本 （12.0版本）。 用友U8财务管理软件12.0版本有以下切题的优势：

- 一整套财务分析功能
- 自动年结账功能
- 内部虚拟局域网应用程序（减少对第三方的依赖，同时节约技术支持和服务的费用）。
- 对最新的操作系统的更全面的支持以及普遍新能改进。 

目前为止已经向用友公司和另外一家财用友代理商询价 （目前还在求其他代理商报价）， 结果如下： 


#### 费用
{: #three-one-one}

##### 用友官方报价
<div class="table-responsive">
	<table class="table table-hover table-bordered">
	  <thead>
	    <tr>
	      <th>#</th>
	      <th>费用大项</th>
	      <th>费用小项</th>
	      <th>小计</th>
	      <th>合计</th>
	    </tr>
	  </thead>
	  <tbody>
	    <tr>
	      <th scope="row">1</th>
	      <th>软件费用</th>
	      <th>-</th>
	      <th class="danger">48,116</th>
	      <th>48,116</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>数据升级费用</th>
	      <th>28个帐套</th>
	      <th class="danger">1500元/帐套</th>
	      <th>42,000</th>
	    </tr>
	    <tr>
	      <th scope="row">3</th>
	      <th>远程应用费用</th>
	      <th>23个许可</th>
	      <th class="danger">1288元/许可</th>
	      <th>29,624</th>
	    </tr>
	    <tr>
	      <th scope="row" colspan="4">项目合计</th>
	      <th class="danger">119,740</th>
	    </tr>
	  </tbody>
	</table>
</div>

#### 代理公司1报价
<div class="table-responsive">
	<table class="table table-hover table-bordered">
	  <thead>
	    <tr>
	      <th>#</th>
	      <th>费用大项</th>
	      <th>费用小项</th>
	      <th>小计</th>
	      <th>合计</th>
	    </tr>
	  </thead>
	  <tbody>
	    <tr>
	      <th scope="row">1</th>
	      <th>软件费用</th>
	      <th>-</th>
	      <th class="success">48,000</th>
	      <th>48,000</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>数据升级费用</th>
	      <th>28个帐套</th>
	      <th class="success">800元/帐套</th>
	      <th>22,400</th>
	    </tr>
	    <tr>
	      <th scope="row">3</th>
	      <th>远程应用费用</th>
	      <th>23个许可</th>
	      <th class="success">800元/许可</th>
	      <th>18,400</th>
	    </tr>
	    <tr>
	      <th scope="row" colspan="4">项目合计</th>
	      <th class="success">88,800</th>
	    </tr> 
	  </tbody>
	</table>
</div>

### 2. OA审批流程平台升级
{: #three-two}

新的OA审批流程平台已经开发好了。这个平台是一个在德国Camunda开放源代码的业务流程引擎的基础之上而编造的审批流程平台。 德国Camunda业务流程引擎由全世界各处的IT管理，软件工程师，以及业务流程等专家每天提供改进与新功能。 另外，Camunda业务流程引擎符合国际认可的业务流程标准BPMN 2.0。

新的平台与以前的相比有以下优势：

- 对最新的浏览器全面支持 （谷歌Chrome, 火狐，微软IE等浏览器）。
- 对移动设备全面支持 （iPad, iPhone 等）。
- 更简化， 更易用， 更现代的用户世面。
- 任何业务流程的支持。
- 易定制。
- 对原编码完全控制。


新的平台已经在云服务器上运行， 可到此网址查询并开始用：

[http://120.26.74.78:8080/camunda/app/tasklist/default/#/login](http://120.26.74.78:8080/camunda/app/tasklist/default/#/login){: target="_BLANK"}

以下为新平台的几张截图：

![金特IT目前组织机构](/img/bpm1.png){: .img-responsive}

![金特IT目前组织机构](/img/bpm2.png){: .img-responsive}

![金特IT目前组织机构](/img/bpm3.png){: .img-responsive}

<!-- ### 3. 官网
{: #three-three}
 -->
---

## 四. 预算
{: #four}

实行此计划会后一个不小的最初开销，而这个最初开销的最大成分为用友U8财务管理软件的升级费用（%90）。考虑到最初我公司购买的U8软件为2009年版本，可算此最初开销等于六年积累的费用，然而此报告错建议采取的结构性变化相对小 （整个预算的18%）。 

我公司若决定实行此计划所建议的措施，预计可将IT相关年开支降低50%。

以下为我公司目前IT相关开支，实行计划的预算以及实行计划后的预计IT相关开支的细目表：

### 1. 公司目前IT年开支
{: #four-one}

每年我公司的IT营运成本为：

<div class="table-responsive">
	<table class="table table-hover table-bordered">
	  <thead>
	    <tr>
	      <th>#</th>
	      <th>项目</th>
	      <th>项目细节</th>
	      <th>费用</th>
	    </tr>
	  </thead>
	  <tbody>
	    <tr>
	      <th scope="row">1</th>
	      <th>中国电信沈家弄机房</th>
	      <th>服务器托管</th>
	      <th>6,800 / 年</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>用友公司U8平台服务费</th>
	      <th>用友公司对我公司用的U8财务管理平台所提供的客服支持费</th>
	      <th>8,600 / 年</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>网络费</th>
	      <th>电信企业网络套餐，配固定IP地址</th>
	      <th>31,180 / 年</th>
	    </tr>
	    <tr>
	      <th scope="row">3</th>
	      <th>科迈公司RAS远程软件服务费</th>
	      <th>科迈公司对我公司用的U8财务管理平台的远程接入软件所提供的客服支持费</th>
	      <th>6,000 / 年</th>
	    </tr>
<!-- 	    <tr>
	      <th scope="row">4</th>
	      <th>企业邮箱</th>
	      <th>企业邮箱</th>
	      <th>40,000</th>
	    </tr> -->
	    <tr>
	      <th scope="row" colspan="3">项目合计</th>
	      <th>52,580</th>
	    </tr>
	  </tbody>
	</table>
</div>


<!-- 
### 费用

<div class="table-responsive">
	<table class="table table-hover table-bordered">
	  <thead>
	    <tr>
	      <th>#</th>
	      <th>项目</th>
	      <th>项目细节</th>
	      <th>费用</th>
	    </tr>
	  </thead>
	  <tbody>
	    <tr>
	      <th scope="row">1</th>
	      <th>沈家弄服务器托管</th>
	      <th>沈家弄服务器托管</th>
	      <th>6800</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>用友服务费</th>
	      <th>财务服务器（用友U8财务软件）整个集团都在用</th>
	      <th>~20,000</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>科迈公司RAS远程软件服务费</th>
	      <th>科迈公司RAS远程软件服务费</th>
	      <th>~20,000</th>
	    </tr>
	    <tr>
	      <th scope="row">3</th>
	      <th>企业邮箱</th>
	      <th>企业邮箱</th>
	      <th>~20,000</th>
	    </tr>
	  </tbody>
	</table>
</div>
 -->



### 2. 公司IT组织机构重组更新活动预算
{: #four-two}
<!-- <div class="table-responsive">
	<table class="table table-hover table-bordered">
	  <thead>
	    <tr>
	      <th>#</th>
	      <th>项目</th>
	      <th>项目细节</th>
	      <th>小计</th>
	    </tr>
	  </thead>
	  <tbody>
	    <tr>
	      <th scope="row">1</th>
	      <th>用友财务平台升级</th>
	      <th>用友财务平台升级</th>
	      <th>96,100</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>云服务器</th>
	      <th>两台: 一台为4,236元/一年，一台为5,676元/一年</th>
	      <th>9,912</th>
	    </tr>
	    <tr>
	      <th scope="row" colspan="3">项目合计</th>
	      <th>106,012</th>
	    </tr> 
	  </tbody>
	</table>
</div>
 -->
 <div class="table-responsive">
	<table class="table table-hover table-bordered">
	  <thead>
	    <tr>
	      <th>#</th>
	      <th>费用大项</th>
	      <th>费用小项</th>
	      <th>小计</th>
	      <th>合计</th>
	    </tr>
	  </thead>
	  <tbody>
	  	<tr>
	      <th scope="row">1</th>
	      <th>Linux云服务器</th>
	      <th>一台</th>
	      <th>4,236元</th>
	      <th>4,236</th>
	    </tr>
	    <tr>
	      <th scope="row">1</th>
	      <th>Windows云服务器</th>
	      <th>一台</th>
	      <th>5,676元</th>
	      <th>5,676</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>用友U8财务平台软件升级费用</th>
	      <th>一个</th>
	      <th>48,000</th>
	      <th>48,000</th>
	    </tr>
	    <tr>
	      <th scope="row">3</th>
	      <th>用友U8财务平台数据升级费用</th>
	      <th>28个帐套</th>
	      <th>800元/帐套</th>
	      <th>22,400</th>
	    </tr>
	    <tr>
	      <th scope="row">4</th>
	      <th>远程应用费用</th>
	      <th>23个许可</th>
	      <th>800元/许可</th>
	      <th>18,400</th>
	    </tr>
	    <tr>
	      <th scope="row">1</th>
	      <th>网络费</th>
	      <th>一年</th>
	      <th>~2,000元</th>
	      <th>~2,000</th>
	    </tr>
	    <tr>
	      <th scope="row" colspan="4">项目合计</th>
	      <th>100,712</th>
	    </tr> 
	  </tbody>
	</table>
</div>


### 3. 公司IT重组更新后预计每年营运成本
{: #four-three}

<div class="table-responsive">
	<table class="table table-hover table-bordered">
	  <thead>
	    <tr>
	      <th>#</th>
	      <th>项目</th>
	      <th>项目细节</th>
	      <th>费用</th>
	    </tr>
	  </thead>
	  <tbody>
	    <tr>
	      <th scope="row">1</th>
	      <th>Linux云服务器</th>
	      <th>一台</th>
	      <th>4,236</th>
	    </tr>
	    <tr>
	      <th scope="row">1</th>
	      <th>Windows云服务器</th>
	      <th>一台</th>
	      <th>5,676</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>用友公司U8平台服务费</th>
	      <th>用友公司对我公司用的U8财务管理平台所提供的客服支持费</th>
	      <th>8,600 / 年</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>网络费</th>
	      <th>电信企业网络套餐，配固定IP地址</th>
	      <th>~2000 / 年</th>
	    </tr>
<!-- 	    <tr>
	      <th scope="row">4</th>
	      <th>企业邮箱</th>
	      <th>企业邮箱</th>
	      <th>40,000</th>
	    </tr> -->
	    <tr>
	      <th scope="row" colspan="3">项目合计</th>
	      <th>20,512</th>
	    </tr>
	  </tbody>
	</table>
</div>



---

## 五. 履行与结论
{: #five}

考虑到IT系统审核所指出的问题，我强烈建议我公司采取此报告所列出的软件更新及机构改组的应对措施。 综上所述，应对措施如下：

1. 用云服务器替换财务服务器及OA系统服务器
2. 将财务软件升级到最新版本。 
3. 将虚拟局域网软件升级到最新版本。
4. 用新的OA系统（已做好）替换目前的OA系统。 

若公司采取此措施，结果会结果会是更简化，更容易管理的IT机构，并且能将每年的营运成本降50%. 


