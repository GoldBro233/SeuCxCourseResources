# 成贤学院课程攻略共享计划

## 前言

来到一所大学，从第一次接触许多课，直到一门一门完成，这个过程中我们时常收集起许多资料和情报。

遇到一门新课，问问学长学姐，这门课怎么样，需要注意什么，老师怎么样，该用什么资料，最后考试怎么复习？我们希望能为每一门课都做一个攻略，花更少的时间，更好地完成课程。把更多的时间用在更有意义的事情上。

受到[浙大课程共享计划](https://github.com/QSCTech/zju-icicles)以及[Z-W-Y/东南大学成贤学院电子与计算机工程学院课程资料](https://github.com/Z-W-Y/SeuCxxyCourseShare/tree/main)的启发。我们决定发起这个项目，希望能帮助到后来的同学，也欢迎各位同学为这个项目贡献自己的一份力量。

由于编者文采限制，本篇 README 大量采用了浙大课程攻略共享计划的内容的 README，特此感谢。

## 特性

本项目目前包含的内容，以及计划包含的内容：

- 课程 PPT
- 课程课外学习资源
- 平时作业答案
- 历年试卷
- 电子版教材
- 复习资料
- 学习经验分享
- 专业介绍以及经验分享

等

## 平台

为什么采用 GitHub 项目作为平台呢？我有以下一些考虑。

QQ 群大多为年级和专业所分隔，无法长期共同地保有；况且群文件也缺乏组织。
GitHub 项目可以使用目录进行文件组织，并且每个目录均可以在显示文件列表的同时显示一个 README，十分适合本项目的需求。
GitHub 带有便捷的 Issue 和 Pull Request 协作功能，并且可以方便地对贡献的质量进行监督和调整。

## 贡献

**欢迎贡献！**

**欢迎贡献！**

**欢迎贡献！**

_——因为很重要所以说了三遍_

Issue、PR、纠错、资料、选课/考试攻略，完全欢迎！

### 操作方法

提交 PR：Fork 本项目，然后在 GitHub 网页端点击 Upload File 上传文件，发起 PR 即可。留意一下项目的文件组织喔。

> 请不要在 Gitee 上创建 Pull Request，因为我们 Gitee 只是一个镜像，不会及时同步。目的是方便翻不了墙的同学。

或者也可以直接附加在 Issue 中，由维护者进行添加。

对于教师的评价请一律使用**姓名拼音首字母缩写**

由于本项目体积很大，故可以采用在 Github Web 端直接上传的方式，具体操作如下：

首先 Fork 本项目

上传文件到已有文件夹：打开对应文件夹，点击绿色 Download 按钮旁的 upload，上传你的文件。

上传文件到新文件夹：打开任意文件夹，点击绿色 Download 按钮旁的 upload，把浏览器地址栏中文件夹名称改为你想要新建的文件夹名称，然后回车，上传你的文件。

### 格式

课程名称请以学院官网课表为准，不要自行缩写。如果课程名称发生了改变，可以修改名称，添加括号并注明旧名称。

同一门课程对不同专业可能有不同的要求，如差距过大，建议开一个新的文件夹，命名为`课程名称-专业名称`。

如果只有资料但不知道是哪个课程的，可以创建一个最可能的课程名称的文件夹，并加上？，如`计算机网络？`。

### commit 规范

如果你会写 commit message，可以参考以下规范：

```
<提交类型>: <概述>
<详细描述>
By: <你的名字>(<联系方式>)
From: <资料来源>
```

- 添加文件：`<提交类型>`为 `add`；`<概述>` 为更新的学科名字（空格分开）；`<详细描述>` 请列举添加文件列表，如有备注也可一并填写
- 修改/整理文件：`<提交类型>`为 `edit`；`<概述>` 为更新（或被删除）的学科名字（空格分开）；`<详细描述>` 请列举修改文件列表，如有备注也可一并填写
- 其他类型提交暂无规范

### 提醒

有些朋友在提交 PR 的时候可能会注意到自己的 Fork 和我们的主分支有数十甚至上百个不同的 commit 。如果出现这种情况，可以考虑以下两种解决方案：

如果对 git 不太熟悉，建议（在备份完成后）先删除你的项目，重新 fork 、上传并重新提交 PR 。
如果对 git 及其工作原理较为熟悉（而且愿意花费时间和流量折腾），可以尝试在 fork 出的项目上进行 rebase 以消除与主分支在历史上的冲突。

### 警告

下列内容为不适合上传的内容。如果你认为缺少这些资料将会影响资源的完整性，请优先考虑放在校内资源平台，或联系你的教师并由教师发布。建议你撰写一个 README 文档并放置一些链接或指引文字来帮助找到这些资源。

<ul style="list-style-type:disc">
    <li>盗版电子书/付费电子书</li>
    <li>盗版/破解版/绿色版付费软件及其安装包</li>
    <li>未经教师授权的课件，资料</li>
    <li>较大的项目工程文件</li>
    <li>较大的课程视频以及多媒体资源</li>
    <li>其他侵权内容</li>
</ul>

如果你认为本仓库的一些文件侵犯了您的权益，请 [向我们发送邮件](mailto:1293915326@qq.com) 或提交 issue/pull request。我们将会从仓库中彻底清除这些文件。

pull request 的使用方法可以参考下面这篇：

[Github pull request 详细教程（提交代码到他人仓库）](https://blog.csdn.net/CY2333333/article/details/113731490)

## 许可

由贡献者编写部分的许可如下：

[CC-BY-NC-SA：署名-非商业性使用-相同方式共享](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)

> 资料仅供参考，请自己判断其适用性。

其他部分的版权归属于其各自的作者。
