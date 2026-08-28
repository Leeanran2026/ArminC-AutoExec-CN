<h1 align="center">
  <br>
  <a href="https://github.com/Leeanran2026/ArminC-AutoExec-CN/archive/refs/heads/main.zip"><img src="https://raw.githubusercontent.com/Leeanran2026/ArminC-AutoExec-CN/main/arminc_autoexec.svg" alt="ArminC AutoExec 简体中文版"></a>
</h1>

<h4 align="center">为玩家打造的高质量 Counter-Strike 2 配置 · 简体中文版</h4>

<p align="center">
    <a href="https://github.com/Leeanran2026/ArminC-AutoExec-CN/commits/main">
    <img src="https://img.shields.io/github/last-commit/Leeanran2026/ArminC-AutoExec-CN.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub last commit">
    <a href="https://github.com/Leeanran2026/ArminC-AutoExec-CN/issues">
    <img src="https://img.shields.io/github/issues-raw/Leeanran2026/ArminC-AutoExec-CN.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub issues">
    <a href="https://github.com/ArmynC/ArminC-AutoExec">
    <img src="https://img.shields.io/badge/原项目-ArmynC%2FArminC--AutoExec-2ea44f?style=flat-square&logo=github&logoColor=white"
         alt="Original project">
</p>

<p align="center">
  <a href="#项目简介">项目简介</a> •
  <a href="#安装">安装</a> •
  <a href="#更新">更新</a> •
  <a href="#功能特性">功能特性</a> •
  <a href="#注释符号说明">注释符号说明</a> •
  <a href="#键位绑定">键位绑定</a> •
  <a href="#致谢">致谢</a> •
  <a href="#支持原作者">支持原作者</a> •
  <a href="#许可证">许可证</a>
</p>

---

> ### 📌 本仓库是什么?
>
> 这是 [**ArmynC/ArminC-AutoExec**](https://github.com/ArmynC/ArminC-AutoExec)(CS2 高质量配置项目)的**简体中文版**:
>
> - 原版全部英文注释已翻译为**中文**,便于中文玩家理解每一项设置的含义;
> - 所有命令、参数、数值与**原版完全一致**,未做任何功能改动;
> - 目录结构与原版相同,可直接放入游戏使用。
>
> 特别感谢原作者 [**ArmynC**](https://github.com/ArmynC) 制作了如此优秀的配置!

---

<table>
<tr>
<td>

**ArminC AutoExec** 是一个高质量的 _Counter-Strike 2_ **配置文件**,通过其模板系统,你可以按自己的喜好自定义游戏设置,从而提升游戏体验。

它内置了大量细微的优化,例如**网络带宽**设置等,全面改善了各种电脑配置和不同类型玩家的游戏体验。

其中每一个命令都经过**精心调校**,与默认设置相比,能充分发挥游戏的潜力。

![ArminC AutoExec Code](https://raw.githubusercontent.com/Leeanran2026/ArminC-AutoExec-CN/main/arminc_autoexec_code.png)
<p align="right">
<sub>(预览)</sub>
</p>

</td>
</tr>
</table>

## 安装

##### 下载与安装步骤:
1. **[下载](https://github.com/Leeanran2026/ArminC-AutoExec-CN/archive/refs/heads/main.zip)** 最新版本的配置。
2. 打开压缩包,**解压** `cfg` 文件夹中的内容到以下路径:<br>
`\...\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\`
3. **启动**游戏,并在 _控制台_ 中输入以下命令:`exec autoexec.cfg`
   * 如果 autoexec 没有自动启动,可以尝试在启动项中添加:`+exec autoexec.cfg`
   * 如果是新电脑或新操作系统(如 Linux),请确保(重新)手动放置所有文件,而不是让 Steam 云自动同步。

> [!IMPORTANT]
> 按键绑定系统已改变。不再使用按键名称,而是为每个按键分配了扫描码(scancode)。

> [!NOTE]
> 准星针对 1920x1080 分辨率设计;在其他分辨率下,体验可能有所不同。

## 更新

当**新版本**发布时,你有**两种方法**来_更新_:

##### 1. 你已根据自己的偏好修改过配置:
* 查看新的[提交记录](https://github.com/Leeanran2026/ArminC-AutoExec-CN/commits/main),并根据提交记录**手动更新**配置。

##### 2. 你没有修改过配置(或修改得不多):
* **删除所有内容**(或在提示时**替换文件**)。
* 重新执行[安装](#安装)步骤。
* _安装完成后_,**恢复**你自己的偏好设置(如果适用)。

## 功能特性

|                            | 🔰 ArminC AutoExec | ◾ 其他配置 |
| -------------------------- | :-----------------: | :---------------: |
| 优化过的数值               |         ✔️         |        〰️        |
| 实用的脚本                 |         ✔️         |        〰️        |
| 启用的游戏内优势           |         ✔️         |        〰️        |
| 有文档说明的命令           |         ✔️         |        ❌        |
| 无错误配置的命令           |         ✔️         |        ❌        |
| 专业的信息来源             |         ✔️         |        ❌        |
| 整洁的模板                 |         ✔️         |        ❌        |
| 易于自定义                 |         ✔️         |        ❌        |
| 按功能分类                 |         ✔️         |        ❌        |
| 新增命令/数值              |         ✔️         |        ❌        |
| 无旧命令残留               |         ✔️         |        ❌        |

## 注释符号说明

      *: 某类目下的多条命令
     >>: 官方描述
    <->: 分析说明
    <i>: 补充信息
    <!>: 重要警告

     /\
     ||: 在提供的范围内选择任意小数/数值
     \/

## 键位绑定
![ArminC AutoExec 键位绑定表(中文)](https://raw.githubusercontent.com/Leeanran2026/ArminC-AutoExec-CN/main/arminc_autoexec_binds_cn_v2.png)

## Wiki

需要**帮助**?请查看[原项目 Wiki](https://github.com/ArmynC/ArminC-AutoExec/wiki/)上的文章。

## 致谢

本项目是 [**ArmynC/ArminC-AutoExec**](https://github.com/ArmynC/ArminC-AutoExec) 的简体中文版,衷心感谢原作者 **ArminC** 的出色工作:

| [![ArminC](https://raw.githubusercontent.com/ArmynC/ArminC-Resources/main/images/a_small.png)](https://github.com/ArmynC) |
|:------------------------------------------------------------------------------------------------------------------------:|
|                                                **ArminC**(原作者)                                                        |

- 原项目:[github.com/ArmynC/ArminC-AutoExec](https://github.com/ArmynC/ArminC-AutoExec)
- 如果喜欢原项目,请前往原仓库点亮 ⭐ Star,支持作者!

## 支持原作者

[![Donation](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-%5E%5E-green?style=flat&logo=undertale&logoColor=green&color=white)](https://github.com/sponsors/armync)

## 许可证

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://tldrlegal.com/license/creative-commons-cc0-1.0-universal)

本仓库与[原项目](https://github.com/ArmynC/ArminC-AutoExec)相同,采用 **CC0 1.0 Universal** 公有领域许可。
