# 面向未来的高级Java系统班课程大纲

高级Java系统班是Java系统班的进阶学习部分，专门针对工作半年以上的Java开发同学，目的只有一个，就是让你升职加薪。

每天做重复的业务，学不到新东西？没关系，来高级系统班学习吧，保证这里的一切都让你大开眼界。

每天都是增删改查，没办法接触高深的技术？没关系，来高级系统班学习吧，高级系统班的配套实战，保证你能在动手过程中掌握你之前从未接触过的知识，在面试中所向披靡。

即将开班的高级系统班分为以下专题，超过30个主题，特点是极其注重实践，每个主题都配套有详细和丰富的练习题和实战训练，辅以详细的源码分析、问题排查实例。能在短时间内迅速提高你的技术能力。之所以要强调这一点，是因为——所有只让你看视频的“架构师课程”都对你的能力提高无济于事。只看视频是学不会东西的，一定要通过`看视频-尝试解决问题-碰壁-回看视频-思考-重试`循环才能提高自己的技术能力。

# 我是谁

如果你是写Java的，那么你应该用过我写的代码——我在[Gradle](https://github.com/gradle/gradle)工作，给包括JDK/Maven在内的众多工具都贡献过代码。换句话说，我是写开源代码为生的，[这是我的GitHub主页](https://github.com/blindpirate)。

# 目录

- [Git/GitHub与团队协作](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#gitgithub%E4%B8%8E%E5%9B%A2%E9%98%9F%E5%8D%8F%E4%BD%9C)
  - [Git高级：拥有解决一切git问题的能力](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#git%E9%AB%98%E7%BA%A7%E6%8B%A5%E6%9C%89%E8%A7%A3%E5%86%B3%E4%B8%80%E5%88%87git%E9%97%AE%E9%A2%98%E7%9A%84%E8%83%BD%E5%8A%9B)
  - [GitHub使用：正确使用GitHub可以让你的日常开发如虎添翼](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#github%E4%BD%BF%E7%94%A8%E6%AD%A3%E7%A1%AE%E4%BD%BF%E7%94%A8github%E5%8F%AF%E4%BB%A5%E8%AE%A9%E4%BD%A0%E7%9A%84%E6%97%A5%E5%B8%B8%E5%BC%80%E5%8F%91%E5%A6%82%E8%99%8E%E6%B7%BB%E7%BF%BC)
  - [GitHub与开源项目协作：向开源项目贡献代码是最容易提高技术的方式，没有之一](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#github%E4%B8%8E%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%E5%8D%8F%E4%BD%9C%E5%90%91%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%E8%B4%A1%E7%8C%AE%E4%BB%A3%E7%A0%81%E6%98%AF%E6%9C%80%E5%AE%B9%E6%98%93%E6%8F%90%E9%AB%98%E6%8A%80%E6%9C%AF%E7%9A%84%E6%96%B9%E5%BC%8F%E6%B2%A1%E6%9C%89%E4%B9%8B%E4%B8%80)
- [向开源项目贡献代码](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E5%90%91%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%E8%B4%A1%E7%8C%AE%E4%BB%A3%E7%A0%81)
  - [向基于GitHub的开源项目贡献代码](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E5%90%91%E5%9F%BA%E4%BA%8Egithub%E7%9A%84%E5%BC%80%E6%BA%90%E9%A1%B9%E7%9B%AE%E8%B4%A1%E7%8C%AE%E4%BB%A3%E7%A0%81)
  - [向OpenJDK贡献代码](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E5%90%91openjdk%E8%B4%A1%E7%8C%AE%E4%BB%A3%E7%A0%81)
- [多线程与并发](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E5%A4%9A%E7%BA%BF%E7%A8%8B%E4%B8%8E%E5%B9%B6%E5%8F%91)
  - [多线程原理](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E5%A4%9A%E7%BA%BF%E7%A8%8B%E5%8E%9F%E7%90%86)
  - [多线程实战：JUC包、Fork/Join与并发流](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E5%A4%9A%E7%BA%BF%E7%A8%8B%E5%AE%9E%E6%88%98juc%E5%8C%85forkjoin%E4%B8%8E%E5%B9%B6%E5%8F%91%E6%B5%81)
- [Docker与容器化](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#docker%E4%B8%8E%E5%AE%B9%E5%99%A8%E5%8C%96)
  - [使用Docker进行日常工作：Docker相当于延长了程序员的生命](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#docker%E4%B8%8E%E5%AE%B9%E5%99%A8%E5%8C%96)
  - [Docker镜像、构建与私有镜像仓库](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#docker%E9%95%9C%E5%83%8F%E6%9E%84%E5%BB%BA%E4%B8%8E%E7%A7%81%E6%9C%89%E9%95%9C%E5%83%8F%E4%BB%93%E5%BA%93)
- [自动化构建、部署与发布](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E8%87%AA%E5%8A%A8%E5%8C%96%E6%9E%84%E5%BB%BA%E9%83%A8%E7%BD%B2%E4%B8%8E%E5%8F%91%E5%B8%83)
  - [自动化测试：主讲人和JUnit的开发者在同一个组工作](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E8%87%AA%E5%8A%A8%E5%8C%96%E6%B5%8B%E8%AF%95%E4%B8%BB%E8%AE%B2%E4%BA%BA%E5%92%8Cjunit%E7%9A%84%E5%BC%80%E5%8F%91%E8%80%85%E5%9C%A8%E5%90%8C%E4%B8%80%E4%B8%AA%E7%BB%84%E5%B7%A5%E4%BD%9C)
  - [自动化构建](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E8%87%AA%E5%8A%A8%E5%8C%96%E6%9E%84%E5%BB%BA)
  - [自动化构建（Maven方向）：将手动劳动自动化](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E8%87%AA%E5%8A%A8%E5%8C%96%E6%9E%84%E5%BB%BAmaven%E6%96%B9%E5%90%91%E5%B0%86%E6%89%8B%E5%8A%A8%E5%8A%B3%E5%8A%A8%E8%87%AA%E5%8A%A8%E5%8C%96)
  - [自动化构建（Gradle方向）](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E8%87%AA%E5%8A%A8%E5%8C%96%E6%9E%84%E5%BB%BAgradle%E6%96%B9%E5%90%91)
- [数据库与缓存高级](https://github.com/hcsp/website/blob/master/高级Java系统班课程大纲.md#数据库与缓存高级)
  - [数据库高级实战](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E6%95%B0%E6%8D%AE%E5%BA%93%E9%AB%98%E7%BA%A7%E5%AE%9E%E6%88%98)
  - [Redis](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#redis)
- [Collection与Stream高级](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#collection%E4%B8%8Estream%E9%AB%98%E7%BA%A7)
  - [Collection高级实战](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#collection%E9%AB%98%E7%BA%A7%E5%AE%9E%E6%88%98)
  - [Lambda、方法引用与Stream](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#lambda%E6%96%B9%E6%B3%95%E5%BC%95%E7%94%A8%E4%B8%8Estream)
- [操作系统与计算机原理高级](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E4%B8%8E%E8%AE%A1%E7%AE%97%E6%9C%BA%E5%8E%9F%E7%90%86%E9%AB%98%E7%BA%A7)  
  - [命令行高级](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E5%91%BD%E4%BB%A4%E8%A1%8C%E9%AB%98%E7%BA%A7)
  - [Java与命令行](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#java%E4%B8%8E%E5%91%BD%E4%BB%A4%E8%A1%8C)
- [数据结构与JDK实现](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E4%B8%8Ejdk%E5%AE%9E%E7%8E%B0)
  - [基本数据结构与JDK实现](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E5%9F%BA%E6%9C%AC%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E4%B8%8Ejdk%E5%AE%9E%E7%8E%B0)
  - [高级数据结构与JDK实现](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E9%AB%98%E7%BA%A7%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84%E4%B8%8Ejdk%E5%AE%9E%E7%8E%B0)
- [深入了解JVM](https://github.com/hcsp/website/blob/master/%E9%AB%98%E7%BA%A7Java%E7%B3%BB%E7%BB%9F%E7%8F%AD%E8%AF%BE%E7%A8%8B%E5%A4%A7%E7%BA%B2.md#%E6%B7%B1%E5%85%A5%E4%BA%86%E8%A7%A3jvm)  

## Git/GitHub与团队协作

### Git高级：拥有解决一切git问题的能力
  - 仓库、提交与分支详解
  - 工作区
  - rebase和merge
    - 【实战】分别使用rebase与merge合并分支
    - 【实战】与任意仓库的任意分支同步代码
  - checkout与reset
    - 【实战】使用checkout将代码库恢复到任意版本
    - 【实战】使用reset对若干次提交进行squash
  - revert
    【实战】revert一个常规commit
    【实战】revert一个merge commit
  - bisect
    - 【实战】通过bisect查找哪个commit引入bug
    - 【实战】使用bisect运行自动脚本
  - stash
    - 【实战】使用stash进行暂存
  - 冲突与解决
  - 在IDEA中使用Git的高级功能
  - Git工作流
    - 【实战】使用Git工作流：feature/bugfix/release
  - cherry-pick
    - 【实战】在master与release分支中使用cherry-pick同步代码
  - 自行搭建Git服务器
    - 【实战】GitLab
    - 【实战】Gogs

### GitHub使用：正确使用GitHub可以让你的日常开发如虎添翼
  - GitHub的基本结构
  - 在GitHub中导航
    - 按照分支、提交以及tag进行检索
    - GitHub资源定位链接
      - Raw data
      - 包含行号的链接
    - 查看Raw文件
    - 查看历史
  - 使用GitHub进行在线git操作
    - 在Web UI上提交代码、建立分支、发起Pull request
    - 比较两份代码（git diff）
    - 分支管理
    - merge/rebase/squash and merge
  - 检索开源项目
    - 如何找到自己想要的开源项目
    - 如何搜索前人提交过的问题
    - 在GitHub中搜索代码、提交、文档

### GitHub与开源项目协作：向开源项目贡献代码是最容易提高技术的方式，没有之一
  - 纪律：开源项目协作流程
  - GitHub的原始仓库与fork
    - 在本地管理多个远程仓库
    - 【实战】将fork的仓库与上游进行同步
  - 检索、发起、关注一个讨论
  - 使用Pull request进行协作
    - 在PR中进行日常code review与沟通
    - 在PR中进行修改建议
    - 三种合并方式详解
  - GitHub API简介与使用 
    - 【实战】搭建一个简单的GitHub机器人 
  - 【实战】GitHub pages搭建博客平台  

## 向开源项目贡献代码

### 向基于GitHub的开源项目贡献代码
  - 基于issue的讨论
  - 本地Fork与问题重现
  - 解决问题并验证
  - 发起Pull request

### 向OpenJDK贡献代码
  - 获取OpenJDK的代码
  - 基于JIRA和邮件组的讨论
  - 本地build JDK
  - 调试、解决问题
  - 生成patch并回馈给OpenJDK社区

## 多线程与并发

### 多线程原理
  - 为什么需要多线程
  - Thread详解
    - Thread是什么
    - Java线程的底层模型
    - Thread的中断
    - ThreadLocal
    - 【实战】使用线程完成基本的多线程操作
    - 【实战】中断一个线程
  - Java的线程模型
    - JMM
    - volatile与可见性
    - 【实战】在多线程中使用volatile改变可见性
  - 线程安全问题
    - 竞争条件
    - 死锁
    - 【实战】将不安全的多线程程序修改成安全的
    - 【实战】死锁的预防、排查和解决
  - 保证线程安全的手段
    - Object.wait/notify/notifyAll模型
    - 【实战】实现生产者/消费者模型
    - synchronized详解
    - synchronized的底层实现
    - 线程安全容器简介

### 多线程实战：JUC包、Fork/Join与并发流    
  - Atomic变量详解
    - CAS
  - ConcurrentHashMap原理
    - 【源码分析】ConcurrentHashMap实现原理与分段锁机制
  - Executor框架与线程池
    - Callable/Future
    - 【实战】线程池调优实战
    - 任务的取消和关闭
  - Lock/Condition
    - AQS框架
    - 【实战】使用
  - CountDownLatch详解与实战
  - CyclicBarrier详解与实战
  - Semaphore/Exchanger详解与实战  
  - Fork/Join框架
    - 【实战】使用Fork/Join实现WordCount程序
  - 并发流
    - 【实战】使用并发流将任务并行化

## Docker与容器化

### 使用Docker进行日常工作：Docker相当于延长了程序员的生命
  - Docker原理与详解
  - 为什么容器化是未来的方向
  - 容器与镜像
  - Docker的基本使用
    - 各参数详解
    - 【实战】使用Docker启动数据库
    - 【实战】使用Docker管理数据库
  - Docker镜像问题排查
    - docker exec
    - 【实战】使用Docker运行NGINX反向代理
    - 【实战】使用Docker运行NGINX进行HTTPS部署
  - k8s简介

### Docker镜像、构建与私有镜像仓库
  - Dockerfile详解
    - Docker分层原理
    - Dockerfile实战
  - 应用的Docker化
    - 【实战】Java
    - 【实战】Go
    - 【实战】Node.js
    - 【实战】Ruby on Rails
  - 搭建私有镜像仓库  
    - 配置私有镜像仓库
    - 为私有镜像仓库配置HTTPS证书
   
## 自动化构建、部署与发布

### 自动化测试：主讲人和JUnit的开发者在同一个组工作
  - 自动化测试简介
  - JUnit 4/5简介
  - JUnit 4/5高级功能
    - 【实战】实现一个JUnit 4的Retry
    - 【实战】实现一个JUnit 5的Extension
  - Mock与测试数据自动化迁移
    - Mockito使用及其原理
    - 【实战】使用H2内存数据库
    - 【实战】使用Docker启动测试数据库
  - 单元测试与集成测试
  - Maven/Gradle测试原理
    - 【实战】在Maven/Gradle中进行自动化测试
  - 【源码剖析】分析著名开源项目的测试代码      

### 自动化构建
  - 什么是自动化构建
  - 在线CI系统travis/CircleCI使用
  - Jenkins从零开始
    - 容器化Jenkins
    - Jenkins基本使用
    - 通过Jenkinsfile将构建逻辑进行版本化管理
    - 使用Jenkinsfile编写自定义UI
    - Jenkins构建的容器化
  - 【实战】基于Jenkins与Docker的自动化发布系统    

### 自动化构建（Maven方向）：将手动劳动自动化
  - Maven的生命周期
    - Maven的命令的本质
  - Maven的阶段、目标与插件
    - 使用Maven插件
    - 在构建中多次使用插件
    - 【实战】编写一个简单的Maven插件
  - Maven的多项目
    - Maven项目的模块化
    - 【源码剖析】著名开源项目多项目结构分析
  - Maven依赖详解
    - Maven中央仓库与本地仓库
    - Maven的坐标与scope
    - 传递性依赖与冲突解决
    - 【实战】包冲突解决实战
  - 搭建Maven仓库私服
  - Maven问题排查与解决
    - 使用调试器解决Maven的构建问题
  - 使用Maven进行jar包的发布与部署
    - 【实战】将jar包发布到私服
    - 【实战】将jar包发布到jcenter/中央仓库
  - 自动化构建
   - 【源码剖析】 分析著名开源项目的Maven构建过程

### 自动化构建（Gradle方向）
  - Gradle简介
    - Wrapper机制
    - Daemon
    - Tooling API
  - Groovy基础
  - Gradle的任务
    - 使用预先定义的任务
    - 编写自定义任务
    - 【实战】编写若干个相互依赖的任务
  - Gradle的生命周期与配置模型
  - Gradle的依赖管理
    - Gradle的坐标与scope
    - 依赖冲突与解决
    - 【实战】Gradle依赖问题排查
  - Gradle多项目
  - Gradle的插件
    - 插件是Gradle的灵魂
    - Script插件
    - buildSrc插件
    - 以jar方式发布的插件  
  - 问题排查与解决
    - 使用调试器解决Gradle的构建问题
    - 使用调试器调试Gradle的测试
  - 使用Gradle进行jar包的发布与部署
    - 【实战】将jar包发布到私服
    - 【实战】将jar包发布到jcenter/中央仓库
  - 自动化构建
   - 【源码剖析】 分析著名开源项目的Gradle构建脚本 

## 数据库与缓存高级

### 数据库高级实战
  - JDBC详解与JDBC数据库管理工具
  - 【实战】Docker安装MySQL/Postgres/H2
  - SQL高级实战
    - JOIN详解
    - JOIN的底层实现
  - 事务
    - 事务的不同隔离等级
    - 【实战】使用Java/MyBatis实现不同的事务隔离等级
  - 索引原理
    - B/B+树简介
    - MySQL索引原理
  - 【实战】根据业务进行索引调优

### Redis
  - Redis入门与简介
  - Redis原理
  - Docker启动Redis
    - 【实战】分布式Redis实例
  - Redis主从模式简介
  - Redis常用命令
    - 【实战】在Java应用中访问Redis
  - 高可用
    - 持久化
    - 集群
    - 动态扩容
    - 原子性  

## Collection与Stream高级

### Collection高级实战
  - equals/hashCode进阶实战
  - HashMap最全详解
    - 【源码剖析】HashMap原理、扩容实现、线程不安全性
    - HashMap在Java8中的改动
  - Comparator/Comparable高级实战  
  - JDK中不常用的Collection实现与重要工具方法
  - 线程安全性
  - 第三方的重要Collection实现与重要工具方法

### Lambda、方法引用与Stream
  - Java 8的巨大改变
    - lambda表达式
    - 函数接口
    - 方法引用
  - Stream原理
    - 中间操作
    - 终结操作
  - Collectors详解
    - 【实战】使用Collectors完成高级数据处理操作
    - 【实战】使用Comparator完成复杂比较器操作
  - 并发流  
    - 【实战】通过并发流提升性能

## 操作系统与计算机原理高级

### 命令行高级
  - 可执行程序与PATH
  - 环境变量
  - 参数与参数的展开
  - 标准输入
  - 标准输入与标准输出
    - 【实战】输出的重定向
  - 管道
    - 【实战】编写管道程序
  - 与操作系统/Shell相关的坑
    - Windows命令行的坑
    - 不同Shell的坑

### Java与命令行
  - Java的启动参数
    - 【实战】编写可以自启动的jar
  - Java的系统属性
    - System property详解
    - 常见系统属性及其用法
  - 在Java中fork子进程
    - 【实战】使用Java代码fork子进程并进行输入/输出

## 数据结构与JDK实现

### 基本数据结构与JDK实现
  - 数组：ArrayList
    - 数据结构详解
    - 【源码剖析】ArrayList
  - 链表：LinkedList
    - 数据结构详解
    - 【源码剖析】LinkedList
  - 栈：Stack/Deque
    - 数据结构详解
    - 【源码剖析】ArrayDeque
  - 哈希表：HashMap
    - 哈希表详解
    - LinkedHashMap的实现
    - 【源码剖析】HashMap
  
### 高级数据结构与JDK实现
  - 二叉树/红黑树：TreeSet/TreeMap 
    - 查找二叉树详解
    - 【源码剖析】TreeMap
    - 【源码剖析】HashMap中的哈希桶实现
  - 堆：PriorityQueue
    - 堆详解
    - 【源码剖析】PriorityQueue
  - 跳表：ConcurrentSkipListMap
    - 跳表详解
    - 【源码剖析】ConcurrentSkipListMap

## 深入了解JVM

### JVM的基本结构与计算模型（Java 8+）
  - 堆
    - 新生代与老年代
    - TLAB
  - 栈
    - 方法栈
    - 线程
  - Metaspace
    - 常量池
    - Class
  - 栈帧
    - 局部变量表
    - 操作数栈
    - 字节码执行引擎
  - 【实战】使用调试器查看JVM的基本结构
  - 【实战】OOM问题排查与解决 
### JVM的字节码与执行系统
  - 字节码结构简介
    - 常量池
    - 访问控制符
    - 方法字节码分析
    - 异常表
    - 调试属性
  - 字节码执行引擎
    - 参数
    - 基于操作数栈的执行引擎
    - 局部变量
    - 返回值  
  - 【实战】使用多种工具分析字节码结构
  - 【实战】使用反编译器阅读字节码
### JVM的类加载机制
  - 类加载的时机和过程
  - 类加载与classpath约定
  - 类加载器
    - 双亲委派模型
    - 上下文类加载器
  - 类加载器与资源
  - 【实战】编写自定义的ClassLoader
### GC（Java 8+）
  - 垃圾回收入门
  - 分代GC
  - GC Roots
  - 常见GC算法简介
    - Serial GC
    - Parallel GC
    - Concurrent Mark and Sweep
    - G1
  - 【实战】切换不同的GC算法
  - 【实战】GC日志分析
### JVM工具与问题排查
  - 死锁问题排查
    - jps与jstack
    - 【实战】排查死锁问题
  - 内存泄漏问题排查
    - MAT与jstat
    - 【实战】排查OOM与内存泄漏问题
  - GC调优
    - 核心概念：延时和吞吐量
    - jstat工具
    - 【实战】High Allocation Rate
    - 【实战】Premature Promotion
    - 【实战】Weak, Soft and Phantom References
  - JVM性能分析
    - perf工具
    - AsyncProfiler与火焰图
    - 【实战】分析并解决JVM的性能问题

## 重构、整洁代码与设计模式

### 重构
  - 重构的必要性
  - 重构：提取公用方法
    - 【实战】提取公用方法
  - 重构：移除注释
    - 【实战】移除注释
  - 重构：抽取公用模块
    - 【实战】抽取公用模块
  - 重构：使用Java 8的特性简化代码
    - 【实战】使用Java 8的特性简化代码

### 设计模式基本实战
  - 单例模式
    - 单例模式简介
    - 【实战】多种方式实现单例模式
  - 工厂方法模式/抽象工厂方法模式
    - 工厂方法模式与抽象工厂方法模式
    - 【源码剖析】分析著名开源项目中的工厂方法模式
  - 建造者模式
    - 建造者模式
    - 【实战】建造者模式
  - 模板模式
    - 模板模式
    - 【实战】模板模式
  - 策略模式
    - 策略模式
    - 【实战】策略模式   

### 设计模式高级实战
  - 访问者模式
    - 访问者模式
    - 【实战】访问者模式
  - 适配器模式
    - 适配器模式
    - 【实战】适配器模式
  - 组合模式
    - 组合模式
    - 【实战】组合模式
  - 装饰器模式
    - 装饰器模式
    - 【实战】装饰器模式
  - 代理模式
    - 代理模式
    - 【实战】代理模式
  - 责任链模式
    - 责任链模式
    - 【实战】责任链模式

## 问题排查与解决

### 调试器高级实战
  - 调试Java世界中的一切程序
  - 调试器高级技巧
    - Conditional breakpoint
    - Evaluate expression
    - Set value
    - Attach source
  - 【实战】使用调试器解决任何疑难问题

## 源码剖析

### Spring深入详解与源码剖析
  - 【源码剖析】Spring 5 IoC容器的启动
  - 【源码剖析】Spring 5 IoC容器创建bean
  - 【源码剖析】Spring 5 AOP
  - 【源码剖析】SpringBoot注解处理器

### JDK深入详解与源码剖析（Java部分）
  - 【源码剖析】ClassLoader
  - 【源码剖析】ThreadLocal
  - 【源码剖析】AtomicInteger
