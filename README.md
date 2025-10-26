<p align="right">
   <strong>中文</strong> | <a href="./docs/README.en.md">English</a>
</p>

<div align="center">

<img src="./docs/images/logo.png" width="120" />

# Academic Agents Studio

### 🤖 新一代学术智能体应用服务平台

<p>
<strong>基于AI智能体驱动的学术研究全流程智能化平台</strong><br>
支持论文写作、文献分析、代码解释、多语言翻译等学术场景
</p>

[![Github][Github-image]][Github-url]
[![License][License-image]][License-url]
[![Python][Python-image]][Python-url]
[![Gradio][Gradio-image]][Gradio-url]
[![Stars][Stars-image]][Stars-url]

[Github-image]: https://img.shields.io/badge/GitHub-Repository-black?style=flat-square&logo=github
[License-image]: https://img.shields.io/badge/License-MIT-orange?style=flat-square
[Python-image]: https://img.shields.io/badge/Python-3.9+-blue?style=flat-square&logo=python
[Gradio-image]: https://img.shields.io/badge/Gradio-Web%20UI-yellow?style=flat-square
[Stars-image]: https://img.shields.io/github/stars/AcademicAgentsStudio?style=flat-square

[Github-url]: https://github.com/AcademicAgentsStudio
[License-url]: https://github.com/AcademicAgentsStudio/blob/master/LICENSE
[Python-url]: https://www.python.org/
[Gradio-url]: https://gradio.app/
[Stars-url]: https://github.com/AcademicAgentsStudio/stargazers

# 免费学术智能体（Academic Agents）MCP服务

![Academic Agents](https://img.shields.io/badge/Academic-Agents-blue.svg)
![Free Service](https://img.shields.io/badge/Service-Free-green.svg)
![Research](https://img.shields.io/badge/Focus-Research-orange.svg)
</div>


## 🎓 项目简介

**免费学术智能体（Academic Agents）MCP服务** 是专为学术研究和科研工作者设计的智能体服务平台。我们致力于为全球研究人员和学者提供高质量、专业化的学术支持服务，通过先进的人工智能技术，全面提升学术研究效率和论文写作质量。

### 🌟 核心理念

- **🆓 免费服务**：全力推动学术智能体服务对学术用户免费开放
- **🔬 学术专业**：专门针对学术场景优化的AI服务
- **🌍 全球服务**：支持多语言，服务全球研究者
- **⚡ 高效便捷**：基于MCP协议，无缝集成到您学术的工作流程

---

## 📊 服务概览

目前已提供核心学术智能体服务，覆盖学术研究的主要需求：

### 1️⃣ 学术写作服务 (FreeAcademicWrite)

**专业的学术文本处理和优化平台**

🔧 **核心功能**：
- **学术语料润色** - 中文学术文本的语法优化、句式改进和可读性提升
- **语法错误检查** - 英文学术文本的精确语法和拼写校对
- **智能翻译** - 自动语言识别，准确翻译各种语言的学术内容
- **学术英中互译** - 针对学术场景的高质量双向翻译服务

🎯 **适用场景**：
- 论文写作与修改
- 学术报告优化
- 研究提案润色
- 国际期刊投稿准备

### 2️⃣ 网络搜索服务 (FreeWebSearch)

**智能化学术信息检索与分析系统**

🔧 **核心功能**：
- **多模型检索** - 集成多种搜索判定模型，精准理解查询意图
- **语义理解** - 深度理解学术查询背景，提供相关性更高的结果
- **实时信息** - 获取最新的研究动态、政策变化和学术资讯
- **全栈检索** - 整合学术数据库、新闻资源、官方文档等多源信息

🎯 **适用场景**：
- 文献调研与综述
- 最新研究动态跟踪
- 政策法规查询
- 背景资料搜集

### 3️⃣ 图表可视化服务 (FreeAcademicChart)

**专业的学术数据可视化解决方案**

🔧 **核心功能**：
- **多类型图表** - 支持条形图、折线图、饼图、环状图、雷达图等10+种图表类型
- **高度定制化** - 自定义标签、数据、颜色和样式配置
- **学术标准** - 符合学术出版标准的图表质量
- **即时生成** - 快速生成高质量图表URL，支持直接引用

🎯 **适用场景**：
- 研究数据可视化
- 论文图表制作
- 学术报告配图
- 数据分析展示

### 4️⃣ 结果格式转换服务 (FreeAcademicFormatter)

**智能化的工具结果格式转换与优化**

🔧 **核心功能**：
- **HTML格式化** - 将外部工具的原始返回结果智能转换为简洁的HTML格式
- **Markdown转换** - 提供文本到Markdown格式的基础转换功能
- **自定义配置** - 支持使用默认大模型进行格式化处理
- **多场景适配** - 优化工具返回内容在前端页面的可视化呈现效果

🎯 **适用场景**：
- 工具返回结果的前端展示
- 学术报告的内容格式化
- 数据可视化前的预处理
- 多格式文档转换

---

## 🚀 快速开始

### 环境要求

- Python 3.8+
- MCP (Model Context Protocol) 客户端

### 服务配置

所有服务均通过 `free_mcp_servers.json` 配置文件进行管理：

```json
{
    "FreeAcademicWrite": {
      "name": "学术智能体（Academic Agents）免费学术写作服务",
      "url": "https://academicwrite.freemcps.aiearth.vip/sse",
      "headers": {
        "Authorization": "Bearer aioagi.tech"
      },
      "description": "学术智能体（Academic Agents）是一个专为学术研究和论文写作设计的智能助手平台，为研究人员和学者提供全方位的学术写作支持，集成四大核心功能：学术语料润色支持中文学术文本的语法优化、句式改进和可读性提升；语法错误检查提供英文学术文本的精确语法和拼写校对；智能翻译具备自动语言识别能力，可准确翻译各种语言的学术内容；学术英中互译专门针对学术场景，运用自然语言处理技术和修辞学知识，在英文和中文之间进行高质量的双向翻译。",
      "enabled": true
    },
    "FreeWebSearch": {
      "name": "学术智能体（Academic Agents）免费网络搜索服务",
      "url": "https://websearch.freemcps.aiearth.vip/sse",
      "headers": {
        "Authorization": "Bearer aioagi.tech"
      },
      "description": "搜索判定等多种检索模型及语义理解，串接专业搜索工程框架及各类型实时信息检索工具，提供实时互联网全栈信息检索，提升 LLM 回答准确性及时效性。",
      "enabled": true
    },
    "FreeAcademicChart": {
      "name": "学术智能体（Academic Agents）免费学术图表可视化服务",
      "url": "https://academicchart.freemcps.aiearth.vip/sse",
      "headers": {
        "Authorization": "Bearer aioagi.tech"
      },
      "description": "支持生成多种类型的图表并返回图表 url，包括：条形图、折线图、饼图、环状图、雷达图、极坐标区域图、散点图、气泡图、径向仪表图、速度表；可定制图表配置，包括：标签、数据和颜色。",
      "enabled": true
    },
    "FreeAcademicFormatter": {
      "name": "学术智能体（Academic Agents）免费结果格式转换服务",
      "url": "https://academicchart.freemcps.aiearth.vip/sse",
      "headers": {
        "Authorization": "Bearer aioagi.tech"
      },
      "description": "支持将外部工具的原始返回结果智能化转换为简洁的HTML格式。使用默认大模型进行格式化处理，同时还提供文本到Markdown格式的基础转换功能。主要用于优化返回内容在前端页面的可视化呈现效果。",
      "enabled": true
    }
}
```

---

## 🔧 技术特色

### 先进架构
- **MCP协议**：采用最新的Model Context Protocol，确保高效通信
- **SSE传输**：基于Server-Sent Events的实时数据传输
- **模块化设计**：每个服务独立部署，互不干扰

### 性能优化
- **智能缓存**：减少重复请求，提升响应速度
- **负载均衡**：支持高并发访问
- **容错机制**：确保服务稳定性

### 安全保障
- **认证授权**：安全的API密钥管理
- **数据隐私**：严格保护用户学术数据
- **服务监控**：实时监控服务状态

---

## 🌍 服务支持

### 语言支持
- **中文**：完整支持简体中文和繁体中文
- **英文**：专业的英文学术文本处理
- **多语种**：支持主要国际语言的翻译服务

### 学科覆盖
- 计算机科学与技术
- 生物医学与生命科学
- 物理学与材料科学
- 化学与化工
- 数学与统计学
- 经济学与管理学
- 人文社会科学

---

## 🚀 发展规划

### 服务扩展计划

我们正在积极开发更多专业的学术智能体MCP服务，以满足研究者在不同场景下的需求：

#### 🔬 即将推出的服务

**📚 学术文献管理服务 (FreeAcademicLibrary)**
- 智能文献检索与推荐
- 引用格式自动生成
- 文献笔记和标注管理
- 学术知识图谱构建

**📊 数据分析服务 (FreeAcademicAnalysis)**
- 统计分析工具集成
- 机器学习模型训练
- 实验数据处理
- 结果可视化与解释

**🤖 学术AI助手服务 (FreeAcademicAssistant)**
- 个性化研究建议
- 学术日程管理
- 同行评议辅助
- 研究项目规划

**🌐 学术协作服务 (FreeAcademicCollaboration)**
- 跨机构研究协作
- 学术资源共享
- 在线学术会议支持
- 知识产权保护

#### 🎯 长期愿景

我们的目标是构建一个完整的**学术智能体（Academic Agents）生态系统**，涵盖学术研究的全生命周期：

1. **研究前期**：文献调研、选题分析、方案设计
2. **研究过程**：数据收集、实验执行、结果分析
3. **成果产出**：论文写作、图表制作、学术发表
4. **知识传播**：学术交流、同行评议、知识共享

## 🌟 加入我们的社区

欢迎加入 **Academic Agents Studio** 学术智能体社区！在这里您可以：

- 💬 **交流使用心得**：分享使用技巧，获取最佳实践
- 🐛 **反馈问题**：报告Bug，提出改进建议
- 🎯 **功能讨论**：参与新功能设计，提出需求建议
- 📚 **学术交流**：与其他学者交流研究心得
- 🚀 **抢先体验**：第一时间体验新功能和版本更新



### 📱 扫码加入群聊

<div align="center">
<table>
<tr>
<td align="center">
<img src="./docs/images/QQ_group.png" width="200" alt="QQ群二维码"/><br>
<strong>🐧 QQ交流群</strong><br>
<em>Academic Agents学术智能体交流群</em>
</td>
<td align="center">
<img src="./docs/images/Wechat_group.png" width="200" alt="微信群二维码"/><br>
<strong>💬 微信交流群</strong><br>
<em>Academic Agents学术智能体交流群</em>
</td>
</tr>
</table>

</div>

> [!TIP]
> **群聊福利**：
> - 🎁 新用户专享配置指南
> - 📖 独家使用教程和模板
> - 🔥 最新功能抢先测试
> - 💡 一对一技术支持
> - 📊 学术资源分享


## 📞 联系与支持

### 技术支持
- **网站**：[https://aioagi.tech](https://aioagi.tech)
- **邮箱**：aioagi@aioagi.tech
- **社区**：加入我们的学术交流群

### 反馈建议
我们非常重视用户的反馈和建议。如果您在使用过程中遇到任何问题，或有功能改进建议，请通过以下方式联系我们：

- GitHub Issues
- 邮件反馈：aioagi@aioagi.tech
- 在线客服：访问官网获取实时支持

---

## 📄 许可协议

本项目采用开源许可协议，免费提供给学术用户使用。请注意：

- ✅ 学术研究使用完全免费
- ✅ 教育机构可自由使用
- ✅ 个人学习与研究不受限制
- ❌ 禁止用于商业目的
- ❌ 禁止恶意使用或滥用服务

---

## 🙏 致谢

感谢所有为学术研究和开放科学做出贡献的研究者和开发者。**免费学术智能体（Academic Agents）** 的使命是通过技术创新推动学术研究的进步，为全球学术共同体提供更好的工具和服务。

---

**🌟 让AI赋能学术研究，让知识创造更高效！**

*© 2025 Academic Agents Studio Team. All rights reserved.*
