# MayaGPT

![Screenshot of MayaGPT running inside Maya](https://i.ibb.co/ynW6b2j/Capturar.png)

一个简单的脚本，用于在 Maya 中集成 openai API，并使用 ChatGPT 使用自然语言提示为 Maya 生成 python 脚本。 
基本上它通过 API 向 openai 发送提示，请求 Maya 的 python 脚本，一旦收到响应的脚本，就执行它。

## 如何使用
您必须生成新的 API 密钥才能使用 ChatGPT api。 创建帐户后，您可以在[此处](https://platform.openai.com/account/api-keys)执行此操作。
另外，为了使其工作，您必须在 Maya 中安装 openai python 模块：
- 在“Autodesk/maya/bin”目录中：运行“mayapy -m pip install openai”.
或者试用一下代码安装openai组件
```bat
cd C:\Program Files\Autodesk\Maya2023\bin
mayapy -m pip install openai
```

在脚本内，将您的 API KEY 插入“openai.api key”变量中。

示例:
[![MayaGPT - ChatGPT for Maya]([https://imgur.com/aguHMw7](https://www.youtube.com/watch?v=ZHKOR4yvfek)
## 常问问题
### 实用吗？
不，存在一些问题，有时它不会生成可用的脚本。 这仍然是一个概念验证，但它确实很重要。 :)

### 我可以在我的作品中尝试或使用它吗？
绝对可以，您可以在您的专业工作环境中自由使用、改进或使用。
