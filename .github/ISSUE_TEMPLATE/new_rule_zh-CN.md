---
name: 提交新规则
about: 为一个应用提交新规则
---

## 基本信息

> 如了解如何使用 JSON 格式编写规则建议，建议使用 Pull Request 向我们提交规则。

- 应用 Id（package name）：

  必填。
  
- 应用显示名称：
  
  必填。

- 应用版本：
  
  可选。

- 是否滥用存储空间：
  
  必填。

- 隔离后是否能正常工作/注意事项：
  
  必填。若存在部分功能无法使用或有特别的注意事项，请说明。

- 对“可访问文件夹”的建议：
  
  可选。如应用有发送图片功能，可以建议将图片文件夹设为可访问文件夹。
  
## “导出被隔离的文件”规则

> 以下内容为“导出被隔离的文件”规则，如需创建规则，请复制多份。如果没有请删除该段落。

### 导出被隔离的文件 01

- 文件类型

  必填。如“保存的图片”。
  
- 来源文件夹（本来在哪里）：
  
  必填。位于隔离存储空间内的文件夹。如 “example/images”。
  
- 目标文件夹（应该在哪里）：

  必填。如 “Pictures/Example”。
  
- 文件名称正则表达式：
  
  可选。只有匹配正则表达式的文件才会被导出。

- 是否需要显示通知：

  必填。适用的场景为下载文件。
  
- 是否需要通知媒体存储：

  必填。适用的场景为保存图片等媒体文件。

## “访问其他应用的文件夹”规则

> 以下内容为“访问其他应用的文件夹”规则，如需创建规则，请复制多份。如果没有请删除该段落。

### 访问其他应用的文件夹 01

- 解决了什么问题：

  必填。

- 来源应用（谁建立了文件）：

  必填。

- 文件夹列表：

  必填。