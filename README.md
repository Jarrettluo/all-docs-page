# all-docs-page
all-docs project introduction page for developers and users.


official homepage：https://jiaruiblog.com/all-docs-page/

---



## 一、介绍



### 1.软件介绍

全文档（All docs) 是一款针对文本类文档的存储、检索、分类管理的知识库管理系统。适合用于中小型团队内进行文档的共享及管理。可支持Linux， Windows，Docker等多种多样的部署；维护简单，可长时间稳定运行。

目前系统所有代码已开源在GitHub，安装文档齐全；同时具有与代码同步的demo系统；建立微信群，方便感兴趣的开发者及使用者交流。



>   同时，作者在开源版的基础上，进一步拓展系统的功能，开发了商业版本。商业版软件除了增加更多人性化的功能以外，增强了系统稳定性和安全性，从各个环节保证保密文档的安全性。如果对系统有二次开发，系统部署等方面的需求，请联系作者，将竭诚为您服务！

### 2.软件特性

-   软件不依赖第三方API，因此支持私有化部署
-   系统存储底层基于MongoDB，系统的文件存储量依赖于数据库的磁盘空间大小。系统本身对存储容量不设限制。
-   系统全文检索依赖ElasticSearch，全文检索的结果及检索的质量取决于全文检索系统本身的性能以及调参等。
-   系统采用无固定模型的设计的方式，因此没有传统的sql文件，在安装系统时，无需进行模型导入。
-   系统维护简单，启动后可长期运行。
-   支持二次开发。系统中预留对各类文档支持的接口，可根据案例进行方便的修改。



### 3.支持的格式

目前支持的文档格式包括：

-   Office文档：.docx, .pptx, .xlsx
-   Pdf文档：.pdf
-   文本文档：.md, .txt, .html
-   其他非文本：.png

### 4.体验地址

与代码同步更新的Demo地址，马上体验：http://81.69.247.172/#/。

![文档分类查看](https://github.com/Jarrettluo/all-docs-page/blob/main/images/Snipaste_2023-05-02_17-25-07.png)



![文档全文检索](https://github.com/Jarrettluo/all-docs-page/blob/main/images/image-20230502172608211.png)

## 二、软件架构

### 1.架构设计

全文档软件系统包括前后端组成。前端采用Vue2.0开发；后端采用Springboot 2.6开发。

整个软件架构包括客户端、代理、服务层、存储层。

![image-20230502162920251](https://github.com/Jarrettluo/all-docs-page/blob/main/images/image-20230502162920251.png)



### 2.客户端的设计



### 3.代理层的设计



### 4.服务层的设计



### 5.存储层的设计





## 三、功能简介图



![image-20230502172323909](https://github.com/Jarrettluo/all-docs-page/blob/main/images/image-20230502172323909.png)



## 四、数据库实体ER图



![image-20230502170314630](https://github.com/Jarrettluo/all-docs-page/blob/main/images/image-20230502170314630.png)





### 

## 五、性能测试

略





## 六、开源项目地址



前端项目：

后端项目：



## 七、Q&A





## 八、联系方式

作者联系方式：luojiarui2@163.com

交流群中转：


