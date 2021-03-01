# 机器学习特别兴趣小组发起草案

## 1. Machine Learning SIG成立的原因

现在越来越的企业在开展机器学习的业务, 而各种机器学习的框架、算法,如tensorflow, pytorch,mxnet, xgboost,它们的部署对于算法工程师或者IT运维人员都带来了不小的挑战，一套稳定、成熟易于扩展的分布式机器学习环境需要操作系统、GPU驱动、框架本身的安装和配置,尤其是相互之间版本的依赖关系尤其复杂, 往往需要数天来完成。随着云原生技术的发展，越来越多的企业开始尝试使用容器技术来搭建自己的学习平台，并催生了各种各样基于kubernetes的机器学习的开源项目，既有端到端的方案Kubeflow,也有专注于特定框架的TorchElastic,还有kubevirt-gpu-device-plugin,aws-virtual-gpu-device-plugin 这类GPU资源虚拟化的kubernetes插件, 为此我们发起了云原生社区机器学习特别兴趣小组\(sig-marchinelearning\)。

## 2. Machine Learning SIG 的成立

SIG专注于Machine learning on kubernetes 领域相关技术，包括传统机器学习、深度学习在kubernets 上的部署、实践。 目前SIG主要关注的项目有Kubeflow TorchElastic, kubevirt-gpu-device-plugin, aws-virtual-gpu-device-plugin。 兴趣小组将致力于这些相关项目的文档翻译, 使用配置实践, 项目发展路线图。同时我们希望有更多不同专业领域经验的人士可以参与进来，不管是你数据科学家、算法工程师、SRE，都可以通过SIG分享相关领域的知识、经验。 我们也将联系上游项目社区, 通过文档、issue修复等活动, 积极参与Machine Learning on kuberneres 生态。

## 3. Machine Learning SIG的责任

我们在不违反法律和相关道德, 并遵守云原生社区公约的前提下,具备以下责任:

* 提供最新、高质量、无偏见且易于使用的材料，帮助最终用户理解并有效采用Machine Learning on kubernetes 领域内的云原生技术和实践，包括并不限白皮书、演示文稿、视频等内容
* 专注与Machine Learning on kubernetes 技术、项目的讨论，分享
* 和上游项目社区对接, 参与各类issue的提交、审核和修复
* 努力成为一个厂商中立, 公开、透明、包容和理解的专注于云原生机器学习领域的SIG小组

## 4. 如何加入 Machine Learning  SIG

最好的方式是加入我们的WeChat Group，我们会通过GitHub, WeChat，以及其他视频会议工具确保让每个参与者理解整个兴趣小组的运作和配合情况，欢迎大家通过群或者issue发表合理的意见、建议。

我们鼓励大家可以在ML/AI 特别兴趣小组里发展自己的特长，共同参与SIG管理、各类活动, 我们希望在这里可以找到志同道合的小伙伴。

## 5. 我们如何运作

同其他云原生社区SIG类似,我们没有固定的工作方式和任务，SIG的活动流程大致如下:

* SIG 会定期组织重点项目的文章、文档翻译, 比如Kubeflow 官方文档的翻译
* SIG 会通过Github SIG仓库\(sig-machinelearning \) issue区发布任务、活动
* SIG 将积极参与云原生社区的活动, 也会与其他社区定时做分享、互动

