<h1 align="center">Mai WebChat Bot</h1>

<div align="center">

[![Github Workflow Status](https://img.shields.io/github/actions/workflow/status/moeakwak/chatgpt-web-share/docker-image.yml?label=build)](https://github.com/moeakwak/chatgpt-web-share/actions)
[![License](https://img.shields.io/github/license/moeakwak/chatgpt-web-share)](https://github.com/moeakwak/chatgpt-web-share/blob/main/LICENSE)

**>>> [English Readme](README.en.md) <<<**

基于[chatgpt-web-share](https://github.com/moeakwak/chatgpt-web-share)进行二次开发，在原有功能基础上，增加语音播放消息。更多新功能正在开发中。
</div>


## 关于项目

个人订制的Web ChatGPT：
- 前后端分离的应用，因此你需要自行部署后端到一个稳定且 IP 可靠的服务器上
- 支持用户管理，并支持设置各用户的权限和对话次数
- 优先支持 ChatGPT Plus 账号

## 特点

- 美观简洁的 web 界面，使用 [naive-ui](https://www.naiveui.com/)
  - 多语言（简体中文、英语）支持
  - 适配夜间模式
  - 支持一键复制回复内容或代码内容
  - 支持显示回复中的图像/表格/数学公式/代码语法高亮
  - 一键导出对话为美观的 Markdown 或 PDF 文件
  - 动态显示回复内容
  - 支持停止生成对话
- 多用户共享管理
  - 创建多用户用于共享一个 ChatGPT 账号
  - 不同用户创建的 ChatGPT 对话互相分隔，不会相互影响
  - 多用户同时请求时，会进行排队处理
  - 管理员可设置用户的最大对话数量、对话次数限制等
  - 提供实时更新的服务使用状态，从而能够避开使用高峰
- 完善的管理功能
  - 修改用户对话限制
  - 管理对话/查看成员对话记录/分配对话给特定用户
  - 实时查看日志
  - 记录请求及对话统计信息

## 部署指南



## 声明

### 调试信息收集和隐私声明


### 风险声明

本项目仅供学习和研究使用，不鼓励用于商业用途。我们不对任何因使用本项目而导致的任何损失负责。

## 捐助和支持

如果觉得本项目对您有帮助，欢迎通过扫描下方赞赏码捐助项目 :)

<img src="docs/donate.png" alt="donate" width="200" height="200" />
