# Ti-Click++

### 团队

队长: 成臣
队员: 杜志刚，何雪薇，张春华，张凯文，高杰磊

### 项目介绍

[Ti-Click官网](https://ti-click.com)

**通过Online IDE的方式，可以让用户以最简便的方式部署Sample App。**

### 项目Demo

[Ti-Click的Example App墙](https://ti-click.com)

### 项目关联Repo
- [Ti-Click Example App List Repo](https://github.com/it2911/ti-click-plus-plus)
- [laravel-with-colopl-tidb-driver-realworld-example-app](https://github.com/ti-click/laravel-with-colopl-tidb-driver-realworld-example-app)
- [conduit-realworld-example-app-base-nodejs](https://github.com/ti-click/conduit-realworld-example-app-base-nodejs)
- [golang-tidb-realworld-example-app](https://github.com/ti-click/golang-tidb-realworld-example-app)
- [realworld-base-django](https://github.com/ti-click/realworld-base-django)

### 现存问题

TiDB是一款有infra属性的产品，所以对开发人员来说，缺乏直观的使用感受。尤其是在对用户进行宣传的时候，会有一些困难。目前面对开发者，我们包括友商提供的仅仅是文档。在github上提供一些Example。但是，要知道，一名开发者在部署一个Example的时候，他要配置环境，下载依赖，进行编译。这些行为麻烦不说，还有可能对他的本地环境产生影响。

### 解决方案

方便快速的开启TiDB开发之旅: 开发人员提供一个基于浏览器的编程环境，开发人员无论是在平板还是电脑上打开浏览器，选择他想尝试的Example，就可以在云端为他提供一个App Example的编程环境。在我们右边的操作台，依次点击导入数据，编译，部署，打开前端页面的按钮，就可以访问一个非常完整，并且带有页面的项目。

### Ti-Click(老版本)

Hackathon 2021 上我们推出了基于Eclipse Che的IDE开发环境，并且为了体现展现了TiDB对多种语言和框架支持的生态多样性，我们支持了包含Python，Java，Nodejs，Golang，PHP,SpingMVC, Django,Laravl多种语言与框架的Sample App。

但是同时也存在两个非常大的问题
1. Eclipse Che的维护
Eclipse Che是一个非常好的Online IDE环境，提供了丰富的功能以及极大的拓展性，但是它的弊端也非常明显。也就是需要自己维护Eclipse Che。Eclipse Che基于Kubernetes提供了Operator的部署方案，虽然部署方案较为成熟，但是如果对Kubernetes的熟练程度不高或者苦于Kubernetes的排错，那么使用Eclipse Che绝对是一个灾难。

2. 耗费资源量巨大
Online IDE因为包含了编程环境，部署环境以及演示环境，所以他所需的资源是惊人的。往往一两位用户的使用，就需要动辄每月几十美金的资源。对于普通企业，这个用户教育成本是非常巨大的。

3. Sample App无法专注于技术本身
尽管Ti-Click提供了繁多的语言与框架的Sample App，但是这些语言和框架也存在着业务不统一的问题。比如说Java的Sample App是宠物医院，但是Python的Sample App却是图书商城。那么对于用户来说，不同的Sample App需要理解不同的业务是非常痛苦的。

### Ti-Click++

我们计划在Hackathon 2022推出Ti-Click的进化版本Ti-Click++，以解决现在存在的问题。

Ti-Click++将使用gitpod的云服务，这样可以一次性解决Eclipse Che运维难和资源消耗问题。此外我们将统一业务模型，使用Real World的模板进行改造。这样可以让用户只需要理解一种业务，但是可以同时理解多种语言链接和使用TiDB的方案。

### Road Map

TODO
