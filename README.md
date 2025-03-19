# AIDE
# 大模型代码能力以及插件探究

## 大模型评估体系

### 1. 多维度评估框架

- **关键指标**：正确性、可维护性（注释完整性）、安全性（漏洞密度）、效率（时间复杂度）

### 2. 跨语言能力评估

* **多语言支持：**java，C++，Python……

- **技术路线**：基于 AST（抽象语法树）或 IR（中间表示）的统一模型架构

### 3. **代码可读性量化**（代码理解）

- 补充命名规范检查（驼峰命名 / 下划线）、代码复杂度（Cyclomatic Complexity）等指标
- 重构建议（如循环展开优化）
- 伪代码

### 4. 人机交互

- **技术路线**：自然语言→代码转换（OpenAPI 规范映射）、交互式对话系统（逐步需求迭代）
- **关键技术**：意图识别（BERT 分类器）、上下文管理（对话历史嵌入）

### 5.**代码调试能力**

### 6.模型策略

* 分层推理架构

- 自适应生成策略
- 学习率调度策略
- 数据增强策略

### 7.评估对象

```
Deepseek r1

Doubao

Qwen2.5 - Coder

DeepSeek Coder
```

```
Code Llama

Star Coder

GPT - 4o

Claude 3.7
```

插件

```
GitHub Copilot
Cursor
Cline
CodeGeeX
通义灵马
```



---

