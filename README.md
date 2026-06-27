# 复旦开源倡议

一个人开源，是一座孤岛；一群人开源，是一片生态。

本倡议只做一件事：**约定一套统一的仓库命名规范**。这样，每个人在 GitHub 上开源的课程文档或项目，都能被同伴便捷地发现、搜索、浏览和学习。

不是为了管理，是为了让彼此看见。

## 为什么需要统一命名

你开源了一份课程笔记、写了一个有趣的项目，但别人怎么找到你？

如果大家各取其名，散落在 GitHub 的各个角落，好东西也会沉没。统一命名 + 统一 topic，就是给自己一个标签、给同伴一个入口：

- 搜 `fdu-courses` 这个 topic，就能看到所有公开的课程仓库
- 搜 `fdu-projects` 这个 topic，就能看到所有公开的项目仓库
- 看到同学在做什么，才知道自己能学什么、能合作什么

## 命名规范

### 课程类

topic: `fdu-courses`

格式：`fdu-course-<课程英文名>-<学期>`

- 课程英文名：教务系统官方英文名称，空格替换为 `-`，统一小写
- 学期：`xxspring` / `xxfall`（如 `25fall`、`26spring`）

示例：
- `fdu-course-algorithms-25fall`
- `fdu-course-machine-learning-26spring`

### 项目类

topic: `fdu-projects`

格式：`fdu-project-<项目名>`

示例：
- `fdu-project-robot-manipulation`
- `fdu-project-llm-wiki`

## 什么是 topics，怎么设置

topics 不是文件夹，不是标签分支，不是提交信息——它是仓库的**分类标签**，显示在仓库主页的 About 区域。别人搜索某个 topic 时，所有打了这个标签的仓库都会出现。

设置方法：打开你的仓库主页 → 右侧 About 栏右侧的齿轮图标 → 在 Topics 输入框中添加对应的 topic。

![topics 设置位置](topics.png)

## 如何参与

1. 按规范命名你的仓库
2. 给仓库打上对应 topic（课程类加 `fdu-courses`，项目类加 `fdu-projects`）

就这样。没有门槛，没有审核，按规范命名、打好 topic，你就是倡议的一部分。

## 许可证

本项目采用 [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) 许可证。

- **署名** — 您必须给出适当的署名，提供指向本许可证的链接，并标明是否进行了更改
- **非商业性** — 您不得将本材料用于商业目的
