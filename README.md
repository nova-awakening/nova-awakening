<div align="center">

# Nova 原生中文编译器

**中文Nova编译器与系统软件工程**

[![CI](https://github.com/nova-awakening/nova-awakening/actions/workflows/ci.yml/badge.svg)](https://github.com/nova-awakening/nova-awakening/actions/workflows/ci.yml)
[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/nova-awakening/nova-awakening/badge)](https://scorecard.dev/viewer/?uri=github.com/nova-awakening/nova-awakening)
[![License](https://img.shields.io/badge/许可证-Nova--CSL%201.1-blue.svg)](NOTICE)
[![Bootstrap](https://img.shields.io/badge/自举-Stage2%20≡%20Stage3-success.svg)]()
[![Language](https://img.shields.io/badge/语言-中文原生-red.svg)]()
[![Platform](https://img.shields.io/badge/平台-x86__64%20Linux-lightgrey.svg)]()
[![Repo Size](https://img.shields.io/github/repo-size/nova-awakening/nova-awakening)](https://github.com/nova-awakening/nova-awakening)
[![Last Commit](https://img.shields.io/github/last-commit/nova-awakening/nova-awakening)](https://github.com/nova-awakening/nova-awakening/commits/master)
[![Commit Activity](https://img.shields.io/github/commit-activity/m/nova-awakening/nova-awakening)](https://github.com/nova-awakening/nova-awakening/commits/master)

**🇨🇳 中文** | [🇬🇧 English](README.en.md)

</div>

## 🌟 项目简介

Nova 是一个围绕**中文原生编程、原生编译能力与系统软件构建**持续推进的工程项目。

- **Nova编译器**：从中文语法到本地代码生成的完整编译链路
- **Nova觉醒**：围绕运行时、系统能力与基础软件协同演进的系统工程
- **中文表达优先**：关键字、标识符、错误消息与工程语义坚持中文原生表达
- **面向长期工程化**：强调可维护性、模块边界与基础软件自主能力

## 🏗️ 仓库内容

```
Nova编译器/    ← 编译器主体、IR、优化、代码生成、内存与工具链实现
Nova觉醒/    ← 系统层模块、运行环境与面向原生软件栈的工程实践
```

## � 发布边界

- 本仓库的 GitHub 正式发布面长期只保留：根目录正式文件、`Nova编译器/` 与 `Nova觉醒/`
- 本地实验目录、自举辅助目录、过程性资料与临时产物默认不进入 GitHub 发布面
- 通过固定点验收的最终Nova编译器二进制将作为独立版本发布物管理，不长期混放在源码发布面中

## 📌 当前发布状态

- **Nova编译器**：当前仓库同步的是源码与固定点演进状态；权威Nova编译器种子以后续版本发布物为准
- **Nova觉醒**：当前仓库同步的是系统源码树，不是正式系统镜像
- **镜像状态**：截至当前版本，`Nova觉醒/` 仍未由当前权威Nova编译器稳定编译为可正式发布的系统镜像，因此本仓库暂不提供系统镜像下载

## �🚀 核心价值

- **中文原生开发体验**：降低中文语境下表达、学习与协作的语义摩擦
- **原生编译能力**：面向本地代码生成与基础软件实现，而非仅停留在解释层
- **系统级协同设计**：编译器与系统工程同步推进，形成统一的软件栈视角
- **自主可控方向**：服务于中文编程语言、基础软件与原生系统能力建设

## 🎯 适用场景

- 中文编程语言与编译器研究
- 原生系统软件与基础软件研发
- 教学、实验、原型验证与技术论证
- 面向 AI 运行环境与自主软件栈的工程探索

## 📜 许可证与合规

**Nova 商业源码许可证 (Nova-CSL 1.1)**：

- **非商业使用**：个人学习、研究、教学及符合许可条款的非商业场景
- **商业使用**：须取得书面商业授权
- **转换后可选开源许可**：自 2032年4月18日起，可在 AGPL-3.0 与木兰公共许可证第2版中任选其一
- **许可文件优先**：具体权利义务以 [LICENSE](LICENSE)、`LICENSE_木兰公共版` 与 [NOTICE](NOTICE) 为准
- **合法合规**：项目遵循知识产权保护与适用法律要求开展开源/源码可用协作

## 💬 联系

- GitHub Issues: [提交问题](https://github.com/nova-awakening/nova-awakening/issues)
- 商业合作与授权：Issues 标注 `[商业授权]`
