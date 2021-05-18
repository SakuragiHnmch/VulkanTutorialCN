# Vulkan 中文教程

该仓库是 [Overv](https://github.com/Overv) 的 [Vulkan 教程](https://github.com/Overv/VulkanTutorial) 的中文镜像仓库，旨在为广大 Vulkan 爱好者提供 Vulkan 教程的中文支持、改善学习体验、扩展 Vulkan 在国内的影响力。

# 翻译完成度

<!-- TODO -->

# 构建与部署

## 安装依赖

由于原仓库基于 [daux](https://github.com/dauxio/daux.io) 文档生成工具构建，所以你需要安装 [PHP](https://www.php.net/) 和 [Composer](https://getcomposer.org/) ，如未安装请自行安装。

我们和原仓库作者都对 daux 工具进行了一定的修改，不过不用担心，我们使用 git submodule 来管理我们的私有修改，你可以直接使用递归克隆指令克隆本仓库：

```shell
git clone --recurse-submodules https://github.com/VulkanTutorialCN/VulkanTutorialCN.git
```

如果已经 clone 了仓库但没有下载 git submodule，你可以使用如下指令更新：

```shell
git submodule init
git submodule update
```

完成后进入 daux 目录，调用如下指令：

```shell
cd daux
composer install
```

即可完成 daux 构建与安装。

## 启用调试服务器

在根目录下调用如下指令：

```shell
daux/bin/daux serve
```

即可看见服务器成功启动：

```
Daux development server started on http://localhost:8085/
```

访问链接即可预览效果。

# 贡献指南

欢迎成为 VulkanTutorialCN 的贡献者，你可以参与的工作如下：

* 提交 [Issue](https://github.com/VulkanTutorialCN/VulkanTutorialCN/issues) 向我们提出问题
* 提交 [Pull Request](https://github.com/VulkanTutorialCN/VulkanTutorialCN/pulls) 来参与翻译 / 校对。

我们会将你的贡献记录在站点中。

# 许可声明

本仓库与原仓库 License 保持一致，采用 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 进行授权。
