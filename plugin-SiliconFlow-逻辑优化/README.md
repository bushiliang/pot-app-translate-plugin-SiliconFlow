# pot-app-translate-plugin-SiliconFlow
SiliconFlow硅基流动翻译插件 - 一个为pot-app开发的翻译插件


## 简介
这是一个基于SiliconFlow API的翻译插件，支持多语言翻译，提供高质量的翻译结果。

## 前置要求
- [pot-app](https://github.com/pot-app/pot-app) - 请先下载并安装pot-app
- [SiliconFlow API开放平台](https://cloud.siliconflow.cn/)- 需要在SiliconFlow官网申请API密钥

## 功能特点
- 支持多种模型选择：推荐使用Qwen2-7B-Instruct版本，响应速度极快，其他的模型例如deepseek-v3速度需要数秒才能响应
- 支持多种语言之间的互译
- 提供专业、流畅的翻译结果

## 安装方法
1. 在pot-app中点击"偏好设置"
2. 选择"服务设置"
3. 点击"翻译-添加外部插件"
4. 选择本插件的发布包进行安装

## 配置说明
1. 选择翻译模型
2. 输入你的SiliconFlow API密钥

## 使用说明
安装并配置完成后，在pot-app的翻译引擎列表中选择"SiliconFlow"即可使用。

## 注意事项
- 请妥善保管你的API密钥
- 翻译服务需要联网使用
- 我只是修改了部分代码，使其支持SiliconFlow。原项目为[pot-app-translate-plugin-deepseek](https://github.com/tzulao55/pot-app-translate-plugin-deepseek?tab=readme-ov-file)- 他拥有这个插件所有的权利。

## 可能遇到的问题
<div align="center">
  <img src="https://github.com/user-attachments/assets/13f21665-aaf4-466c-84ba-eed752deb14c" width="60%">
</div>

- 如果在导入之后进行翻译，SiliconFlow没有冒泡泡进行翻译的活（就像上面这样）
- 你可以通过pot的服务设置中选择SiliconFlow插件设置，重新选择一下模型，然后保存后再试试。



