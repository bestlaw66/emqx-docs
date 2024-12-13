# 宝塔面板 上安装 EMQX

本页将指导您如何在 宝塔面板 安装并启动 EMQX。

支持的 宝塔面板 版本：

- 宝塔面板版本 9.2.0 及以上

当你需要通过 宝塔面板 部署本项目之前，需要在服务器上先安装好 宝塔面板工具。 接下来的 部署流程 都建立在已有宝塔面板的前提下。
宝塔安装请参考 ([宝塔官网](https://www.bt.cn/new/download.html?r=dk_emqx))

## 一键安装
![install1](https://github.com/user-attachments/assets/4e45da0b-879b-47fd-aa8d-aa4dde682286)
1. 在 宝塔面板 -> Docker -> 应用商店 页面，搜索 emqx 找到本项目的docker应用；
2. 点击 安装 开始部署本项目

![install2](https://github.com/user-attachments/assets/62fe5ea4-395d-4290-8fc6-7207977f4215)
1. 在项目配置页，根据要求开始配置环境变量；
2. 如勾选 允许外部访问 配置，请注意为配置的 web端口 开放安全组端口访问权限；
3. 点击 确认 开始自动部署。

## 如何访问
通过根据 服务器IP地址 和配置的 web端口 http://$(host):$(port)，在浏览器中打开 emqx。
![install3](https://github.com/user-attachments/assets/5c629fca-60f2-4859-aa09-3fc4e0dcfec5)

相关的配置信息可以点看容器详情查看
![install4](https://github.com/user-attachments/assets/149703db-1091-449e-bba4-77507d70007a)

