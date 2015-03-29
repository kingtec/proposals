---
layout: post
title:  "金特集团IT改组方案"
date:   2015-03-26 10:00:00
categories: proposals
---

现在集团的IT结构存在着一个问题，迟早需要结局，以下为集团的目前IT形式的简报以及重组和改善集团IT结构的方案。

---

## 金特集团IT形式

我公司IT形式最大问题如下：

- 服务器硬件落后。
- 操作系统很落后
- OA系统落后
- 财务管理软件落后
- 太多第三方的参与



我公司在临汾路的办公室和浦东沈家路的机房都留着服务器。 这并不是最理想的情况，因为：

- 这种非集中性的形式在管理的方面上会带来很多不便。 
- 临汾路办公室的互联网环境不妙（作为居民区很难满足企业的条件，稳定性不高）。
- 沈家路的机房算是下层的机房，安全性很弱 （我好次几叫他们重启服务器，也没有人确认过我的身份）。

目前我公司的服务器全都装了Windows2003年服务器系统。这款系统不但很老，微软也已经宣布从2015年7月14日将停止对这款系统的支持。虽然这款系统到时候依然能偶运行，但是失去了微软提供的安全更新，服务器就会成为黑客的靶子。 我公司最好采取升级系统的措施。


每年我公司的IT开支如下：

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
	      <th>沈家路服务器托管</th>
	      <th>沈家路服务器托管</th>
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


### 云服务器： 省钱 + 省麻烦

云服务器是未来。互联网企业（比如阿里巴巴）的服务器和机房不计其数，所以它们可以把大规模效应带来的经济节约传给最终客户。这个新的形势能让企业把硬件管理，软件管理，和安全忧虑都外包出去。 云服务器的另外优势在于它的定价方案。因为云服务是虚拟服务器（了解关于虚拟服务器的更多信息：）, 所以可以随时调整配置。 比如随时调内存，硬盘内存，CPU核的数量，系统版本， 宽带网速等。 最为重要的是，云服务器比传统服务器托管服务便宜，而这还不包括硬件的费用。



阿里云Linux服务器（OA系统 + 公司网站） 

<img class="img-responsive" src="/img/aliyun1.png">

阿里云Windows服务器（用友U8财务软件） 

<img class="img-responsive" src="/img/aliyun2.png">



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
	      <th>沈家路服务器托管</th>
	      <th>沈家路服务器托管</th>
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




#### IT目前结构形式图

<img class="img-responsive" src="/img/金特IT情况.svg">

#### IT理想结构形式图

<img class="img-responsive" src="/img/金特IT理想情况2.svg">

---

### 硬件情况

<div class="table-responsive">
	<table class="table table-hover table-bordered">
	  <thead>
	    <tr>
	      <th>#</th>
	      <th>硬件</th>
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
	      <th>火墙，宽带流量控制</th>
	      <th>Windows 2003 服务器系统</th>
	      <th>上海临汾路1368号</th>
	      <th>系统较老，需更新</th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>联想转用服务器</th>
	      <th>财务服务器（用友U8财务软件）整个集团都在用</th>
	      <th>Windows 2003 服务器系统</th>
	      <th>上海临汾路1368号</th>
	      <th>系统较老，需更新</th>
	    </tr>
	    <tr>
	      <th scope="row">3</th>
	      <th>联想主机（转变为服务器）</th>
	      <th>火墙，宽带流量控制</th>
	      <th>Windows 2003 服务器系统</th>
	      <th>上海临汾路1368号</th>
	      <th>系统较老，需更新，目前没人用</th>
	    </tr>
	    <tr>
	      <th scope="row">4</th>
	      <th>联想主机（转变为服务器）</th>
	      <th>火墙，宽带流量控制</th>
	      <th>Windows 2003 服务器系统</th>
	      <th>上海电信沈家弄机房（沈家弄路650号）</th>
	      <th>系统较老，需更新，目前没人用</th>
	    </tr>
	  </tbody>
	</table>
</div>

### 软件，服务情况及费用

<div class="table-responsive">
	<table class="table table-hover table-bordered">
	  <thead>
	    <tr>
	      <th>#</th>
	      <th>软件</th>
	      <th>用途</th>
	      <th>状态</th>
	      <th>费用</th>
	    </tr>
	  </thead>
	  <tbody>
	    <tr>
	      <th scope="row">1</th>
	      <th>用友U8财务软件，980版本（2008年）</th>
	      <th>基本财务管理软件</th>
	      <th>整个集团正在用。此版本很老，<br>建议更新到最新版本。每年得交服务费</th>
	      <th></th>
	    </tr>
	    <tr>
	      <th scope="row">2</th>
	      <th>科迈RAS远程软件。</th>
	      <th>虚拟局域连接软件，<br>使能够外雇员能够安全地连接到财务服务器</th>
	      <th>到现在没什么大的问题，不过稳定性不高，<br>外地会计偶尔会遇到打印不了账单的故障。</th>
	      <th></th>
	    </tr>
	    <tr>
	      <th scope="row">3</th>
	      <th>网易企业邮箱</th>
	      <th>集团@kingtec.cc的企业邮箱服务</th>
	      <th>到目前为止对此服务十分满意。优质产品。</th>
	      <th></th>
	    </tr>
	    <tr>
	      <th scope="row">4</th>
	      <th>OA系统</th>
	      <th>办公平台，审批流程，考核</th>
	      <th>只支持IE8.0以下版本的浏览器，<br>不支持移动设备的浏览器, 用户界面过时，<br>调整流程的过程极复杂，各个方面不足。</th>
	      <th>一次性费用</th>
	    </tr>
	  </tbody>
	</table>
</div>

---

## 用友U8平台升级

目前我公司的财务服务器装了用友U8财务平台9.80版本，此版本于2008年上市，总算是比较老的版本。 
此版有以下缺点：

- 缺少最基本的财务分析功能
- 每年的帐套结转必须得手工操作，易于犯错误。 
- 用户界面过时，很多新来的会计已习惯使用更新的版本。 

现在建议升级到最新的版本 （12.0版本）， 还建议同时把远程虚拟局域软件升级到最新的版本，以解决打印机常断开连接的问题。 

### 费用

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
	      <th class="success">1288元/许可</th>
	      <th>29,624</th>
	    </tr>
	    <tr>
	      <th scope="row" colspan="4">项目合计</th>
	      <th class="danger">119,740</th>
	    </tr>
	  </tbody>
	</table>
</div>

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
	      <th class="danger">2,800元/许可</th>
	      <th>25,700</th>
	    </tr>
	    <tr>
	      <th scope="row" colspan="4">项目合计</th>
	      <th class="success">96,100</th>
	    </tr> 
	  </tbody>
	</table>
</div>

---

## 结论 - 预算

<div class="table-responsive">
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
