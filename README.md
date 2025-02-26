# LLM 并发测试工具

## 项目简介
本项目用于测试大型语言模型（LLM）的并发性能，包括响应时间、token生成速度等指标。通过多线程并发请求，可以评估模型在高负载情况下的表现。

## 功能特性
- 支持流式响应处理
- 多线程并发测试
- 详细的性能指标记录
  - 首token延迟
  - 非首token平均延迟
  - 每秒生成token数
  - 输入/输出token数
- 测试结果自动保存为CSV文件

## 快速开始

### 环境要求
- Python 3.7+
- 依赖库：
  - requests
  - concurrent.futures

### 安装依赖
```bash
pip install -r requirements.txt