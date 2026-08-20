# 鹈鹕自行车大模型测试（Pelican Bicycle Benchmark）

[English](README.md) | 简体中文

SVG生成基准测试

## 测试方法

- 所有模型输入**完全相同**的提示词：`generate an svg of a pelican riding a bicycle`
- 输出结果按 `厂商/模型/` 目录分类存放

## 结果总览

共 8 家厂商、13 个模型。厂商按其最早模型的发布时间排列，同一厂商内的模型按发布时间先后排序。

| 厂商 | 模型 | 发布时间 | 思考强度 | 输出文件 |
|---|---|---|---|---|
| Anthropic | Claude Opus 4.7 | 2026-04-16 | max | `claude/claude-opus-4.7/opus-4.7-max.png` |
| Anthropic | Claude Opus 4.8 | 2026-05-28 | max | `claude/claude-opus-4.8/opus-4.8-max.jpg` |
| Anthropic | Claude Fable 5 | 2026-06-09 | max | `claude/claude-fable-5/fable-5-max.jpg` |
| Anthropic | Claude Sonnet 5 | 2026-06-30 | max | `claude/claude-sonnet-5/sonnet-5-max.png` |
| OpenAI | GPT-5.5 | 2026-04-23 | xhigh | `GPT/gpt-5.5/gpt-5.5-pelican-xhigh.png` |
| OpenAI | GPT-5.6 Luna | 2026-07-09 | high / xhigh / max | `GPT/gpt-5.6-luna/` |
| OpenAI | GPT-5.6 Sol | 2026-07-09 | high / xhigh / max | `GPT/gpt-5.6-sol/` |
| OpenAI | GPT-5.6 Terra | 2026-07-09 | high / xhigh / max | `GPT/gpt-5.6-terra/` |
| DeepSeek | DeepSeek V4 Flash | 2026-07-31 | max | `DeepSeek/deepseek-v4-flash/v4-flash.png` |
| DeepSeek | DeepSeek V4 Pro | 2026-08-13 | max | `DeepSeek/deepseek-v4-pro/v4-pro.png` |
| 小米 | MiMo v2.5 Pro | 2026-04-27 | max | `xiaomi/mimo-v2.5-pro/mimo-v2.5-pro.png` |
| 智谱 | GLM-5.2 | 2026-06-16 | max | `GLM/glm-5.2/glm-5.2-max.jpg` |
| 智谱 | GLM-5.3 | 2026-08-14 | max | `GLM/glm-5.3/glm-5.3-max.png` |
| 月之暗面 | Kimi K3 | 2026-07-16 | max | `Kimi/kimi-k3/kimi-3-pelican.jpg` |
| 阿里巴巴 | Qwen 3.8 Max | 2026-08-03 | max | `Qwen/Qwen-3.8-Max/qwen-3.8-max-pelican.png` |
| 阿里巴巴 | Qwen 3.8 27B | 2026-08-14 | max | `Qwen/Qwen-3.8-27B/qwen-thinking-bicycle-27b.jpg` |
| Meta | Muse Spark 1.2 | 2026-08-05 | max | `meta/muse-spark-1.2/muse-spark-1.2.png` |

## 各模型输出

### Anthropic

| | |
|---|---|
| **Claude Opus 4.7**<br>2026-04-16<br><img src="claude/claude-opus-4.7/opus-4.7-max.png" width="300" alt="Claude Opus 4.7"> | **Claude Opus 4.8**<br>2026-05-28<br><img src="claude/claude-opus-4.8/opus-4.8-max.jpg" width="300" alt="Claude Opus 4.8"> |
| **Claude Fable 5**<br>2026-06-09<br><img src="claude/claude-fable-5/fable-5-max.jpg" width="300" alt="Claude Fable 5"> | **Claude Sonnet 5**<br>2026-06-30<br><img src="claude/claude-sonnet-5/sonnet-5-max.png" width="300" alt="Claude Sonnet 5"> |

### OpenAI

**GPT-5.5**（2026-04-23，xhigh）

<img src="GPT/gpt-5.5/gpt-5.5-pelican-xhigh.png" width="300" alt="GPT-5.5">

**GPT-5.6**（2026-07-09）

| | high | xhigh | max |
|---|---|---|---|
| **Luna** | <img src="GPT/gpt-5.6-luna/high/high.png" width="260" alt="GPT-5.6 Luna high"> | <img src="GPT/gpt-5.6-luna/xhigh/xhigh.png" width="260" alt="GPT-5.6 Luna xhigh"> | <img src="GPT/gpt-5.6-luna/max/max.png" width="260" alt="GPT-5.6 Luna max"> |
| **Sol** | <img src="GPT/gpt-5.6-sol/high/high.png" width="260" alt="GPT-5.6 Sol high"> | <img src="GPT/gpt-5.6-sol/xhigh/xhigh.png" width="260" alt="GPT-5.6 Sol xhigh"> | <img src="GPT/gpt-5.6-sol/max/max.png" width="260" alt="GPT-5.6 Sol max"> |
| **Terra** | <img src="GPT/gpt-5.6-terra/high/5.6-terra-high.png" width="260" alt="GPT-5.6 Terra high"> | <img src="GPT/gpt-5.6-terra/xhigh/5.6-terra-xhigh.png" width="260" alt="GPT-5.6 Terra xhigh"> | <img src="GPT/gpt-5.6-terra/max/5.6-terra-max.png" width="260" alt="GPT-5.6 Terra max"> |

### DeepSeek

| | |
|---|---|
| **DeepSeek V4 Flash**<br>2026-07-31<br><img src="DeepSeek/deepseek-v4-flash/v4-flash.png" width="300" alt="DeepSeek V4 Flash"> | **DeepSeek V4 Pro**<br>2026-08-13<br><img src="DeepSeek/deepseek-v4-pro/v4-pro.png" width="300" alt="DeepSeek V4 Pro"> |

### 小米

**MiMo v2.5 Pro**（2026-04-27）

<img src="xiaomi/mimo-v2.5-pro/mimo-v2.5-pro.png" width="300" alt="MiMo v2.5 Pro">

### 智谱

| | |
|---|---|
| **GLM-5.2**<br>2026-06-16<br><img src="GLM/glm-5.2/glm-5.2-max.jpg" width="300" alt="GLM-5.2"> | **GLM-5.3**<br>2026-08-14<br><img src="GLM/glm-5.3/glm-5.3-max.png" width="300" alt="GLM-5.3"> |

### 月之暗面

**Kimi K3**（2026-07-16）

<img src="Kimi/kimi-k3/kimi-3-pelican.jpg" width="300" alt="Kimi K3">

### 阿里巴巴

| | |
|---|---|
| **Qwen 3.8 Max**<br>2026-08-03<br><img src="Qwen/Qwen-3.8-Max/qwen-3.8-max-pelican.png" width="300" alt="Qwen 3.8 Max"> | **Qwen 3.8 27B**<br>2026-08-14<br><img src="Qwen/Qwen-3.8-27B/qwen-thinking-bicycle-27b.jpg" width="300" alt="Qwen 3.8 27B"> |

### Meta

**Muse Spark 1.2**（2026-08-05）

<img src="meta/muse-spark-1.2/muse-spark-1.2.png" width="300" alt="Muse Spark 1.2">
