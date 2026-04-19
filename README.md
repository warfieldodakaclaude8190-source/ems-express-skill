# EMS快递Skill

## 项目简介

EMS快递Skill提供中国邮政速递物流的全方位服务。本Skill集成了EMS官方服务，为用户提供便捷的快递查询、寄件预约、网点查询等功能。

## 仓库地址

- https://github.com/warfieldodakaclaude8190-source/ems-express-skill

## 关于EMS

中国邮政速递物流股份有限公司（简称中国邮政速递物流、EMS）是经国务院批准，由中国邮政集团公司作为主要发起人，于2010年6月发起设立的股份制公司，是中国经营历史最悠久、网络覆盖范围最广的快递物流综合服务提供商。

- **核心业务**：国内速递、国际速递、合同物流
- **网络覆盖**：国内31个省（自治区、直辖市），通达全球200余个国家和地区
- **服务理念**：珍惜每一刻，用心每一步

## 这个Skill能做什么

- **快速下单通道**：便捷的在线寄件下单服务，支持填写寄件人和收件人信息，选择快递服务类型和付款方式，一键生成运单并安排上门取件
- **查快递**：输入快递单号（高考录取通知书）查询物流状态，支持实时物流更新和详细的物流轨迹信息，支持批量查询和历史记录管理
- **网点查询**：按省—市—区三级行政区划逐层展开查询，提供网点详细地址、联系电话和营业时间，支持地图定位和导航
- **寄件预约**：在线预约寄件服务，填写寄件人和收件人信息，选择寄件时间和地点
- **价格查询**：根据寄件和收件地址查询快递费用，支持不同重量和尺寸的价格估算，提供多种快递服务类型的价格对比
- **快递常识**：快递包装指南、禁寄物品查询、国际快递须知、快递时效说明
- **在线客服**：常见问题解答、人工客服咨询、投诉与建议

## 目录结构

```text
ems-express-skill/
├── SKILL.md      # Skill主要文件
├── README.md     # 项目说明文件
├── LICENSE       # 开源许可证文件
└── scripts/      # 预留目录
```

## 安装和使用

1. 克隆仓库：

```bash
git clone git@github.com:warfieldodakaclaude8190-source/ems-express-skill.git
```

2. 将 Skill 部署到 Trae 平台的 Skill 目录。
3. 在 Trae 环境中启用并测试 EMS 快递功能。

如果你希望用 AI 助手自动安装，可以直接发送下面这句话：

```text
帮我安装 EMS 快递 Skill ，仓库地址：https://github.com/warfieldodakaclaude8190-source/ems-express-skill
```

Agent 会自动克隆仓库并安装到对应的 Skill 目录。

## 发布平台

- **Trae IDE**：支持在Trae集成开发环境中使用
- **Trae Assistant**：可通过Trae智能助手调用

## 技术协议

- **开发平台**：Trae Skills Framework
- **数据接口**：EMS官方API
- **通信协议**：HTTPS
- **响应格式**：JSON

## 版本信息

- **当前版本**：1.0.0
- **发布日期**：2026-04-18
- **更新内容**：
  - 初始版本发布
  - 集成EMS官方服务
  - 实现快速下单、查快递、网点查询等核心功能

## 许可证

本项目采用MIT许可证。

```
MIT License

Copyright (c) 2026 好雨知时节/广东深圳

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 贡献指南

欢迎贡献改进本项目：

1. Fork 本仓库。
2. 新建分支：`feature/your-feature` 或 `fix/your-bug`。
3. 提交代码并编写简要说明。
4. 提交 Pull Request，并描述你的修改内容。

建议修改内容包括：

- 修复或优化 Skill 逻辑
- 增强功能说明和示例
- 完善文档、注释、README

## 问题反馈

如果你发现问题或有功能建议，请在仓库 Issue 中提交详细描述，并附上重现步骤。

## 使用示例

### 查快递

```text
用户：帮我查一下快递单号 EM123456789CN
助手：正在查询您的快递信息...
```

### 网点查询

```text
用户：帮我找一下北京朝阳区的EMS网点
助手：为您查询北京朝阳区EMS网点...
```

### 寄件预约

```text
用户：我想预约寄件，从北京到上海
助手：请提供寄件人和收件人信息...
```

## 开发者说明

本项目基于 Trae Skills Framework 开发：

- **Skill 配置**：`SKILL.md` 包含 Skill 定义和配置
- **API 集成**：使用 EMS 官方 API 接口
- **数据格式**：所有响应采用 JSON 格式
- **错误处理**：包含完善的异常处理机制

## 技术支持

如有任何问题或建议，请联系：
- EMS客服热线：11183
- 项目维护者：好雨知时节/广东深圳