# Linux 系统——从小白学起

一本面向小白的 Linux 学习教程。

## 简介

这本书希望以最简洁明了的方式，帮助刚刚接触文本用户界面的小白快速上手 Linux。本书的任务，是帮助你掌握一些技能，这些技能足够你在 Linux 上应付大学课程中的需要做的各种实验、处理经常见到的一些错误（那些实验的手册通常不会对 Linux 的使用进行详细的讲解，且常常不能解决自己配置环境时产生的错误）。

从 WSL 的安装开始，我们将逐步讲解命令行、环境配置、程序编译及调试和 Linux 实用工具等内容。我们不会打算详细讲解 Vim 和 Git 等内容，因为这对于本书的目标不是必要的，但我们很希望你去自学它们。我们会在书本最后一章提供一些深入内容的链接，期待你进一步探索。

市面上其实已经有不少优秀的 Linux 中文书籍，比如《Linux 就该这样学》，但它们大多面向服务器运维人员，使用 CentOS。而在大学学习过程中，我们一般使用基于 Ubuntu 的 WSL，两者环境略有差异，且技能侧重点也不同。因此，我们打算建立这样一个教程。

## 项目构建

本书基于 [MkDocs](https://www.mkdocs.org/getting-started/) 和 [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/getting-started/) 构建。

## 仓库结构

- `src` 书中的做的实验、脚本等的源码。
- `ref` 本书用到的参考资料（仅上传纯电子版文件，要求文件体积 <= 10MB）
- `docs` 笔记正文内容 

## 贡献

除了遵守 [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines) 和 [中文技术文档的写作规范——Ruan YiFeng](https://github.com/ruanyf/document-style-guide) 的通用排版格式以外，本书有一些基本的约定。

- 每个关键名词第一次出现在文中时，都会加粗并在括号内写出英文单词。