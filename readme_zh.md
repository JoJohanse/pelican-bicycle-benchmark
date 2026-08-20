# Pelican Bicycle Benchmark

[English](README.md) | 简体中文

测试各大模型 SVG 生成能力的项目。

## 测试方法

- 所有模型输入**完全相同**的提示词：`generate an svg of a pelican riding a bicycle`
- 输出结果按 `厂商/模型/` 目录分类存放
- 未标注思考强度的图片均为**最大思考强度**下输出
- 部分目录同时保存 SVG 源文件与 PNG 渲染图

## 结果总览

共 8 家厂商、13 个模型。

| 厂商 | 模型 | 思考强度 | 输出文件 |
|---|---|---|---|
| Anthropic | Claude Fable 5 | max | `claude/claude-fable-5/fable-5-max.jpg` |
| Anthropic | Claude Opus 4.7 | max | `claude/claude-opus-4.7/opus-4.7-max.png` |
| Anthropic | Claude Opus 4.8 | max | `claude/claude-opus-4.8/opus-4.8-max.jpg` |
| Anthropic | Claude Sonnet 5 | max | `claude/claude-sonnet-5/sonnet-5-max.png` |
| DeepSeek | DeepSeek V4 Flash | — | `DeepSeek/deepseek-v4-flash/pelican-bicycle.svg` |
| DeepSeek | DeepSeek V4 Pro | — | `DeepSeek/deepseek-v4-pro/pelican-bicycle.svg` |
| Z.ai | GLM-5.2 | max | `GLM/glm-5.2/glm-5.2-max.jpg` |
| Z.ai | GLM-5.3 | max | `GLM/glm-5.3/glm-5.3-max.svg`（附 PNG 渲染图） |
| OpenAI | GPT-5.5 | xhigh | `GPT/gpt-5.5/gpt-5.5-pelican-xhigh.png` |
| OpenAI | GPT-5.6 Luna | high / xhigh / max | `GPT/gpt-5.6-luna/` |
| OpenAI | GPT-5.6 Sol | high / xhigh / max | `GPT/gpt-5.6-sol/` |
| OpenAI | GPT-5.6 Terra | high / xhigh / max | `GPT/gpt-5.6-terra/`（各含 SVG 与 PNG） |
| Moonshot | Kimi K3 | — | `Kimi/kimi-k3/kimi-3-pelican.jpg` |
| Meta | Muse Spark 1.2 | — | `meta/muse-spark-1.2/pelican_bicycle.svg` |
| Alibaba | Qwen 3.8 27B | — | `Qwen/Qwen-3.8-27B/qwen-thinking-bicycle-27b.jpg` |
| Alibaba | Qwen 3.8 Max | — | `Qwen/Qwen-3.8-Max/qwen-3.8-max-pelican.png` |
| Xiaomi | MiMo v2.5 Pro | — | `xiaomi/mimo-v2.5-pro/pelican-on-bike.svg` |

## 各模型输出

### Anthropic

#### Claude Fable 5

![Claude Fable 5](claude/claude-fable-5/fable-5-max.jpg)

#### Claude Opus 4.7

![Claude Opus 4.7](claude/claude-opus-4.7/opus-4.7-max.png)

#### Claude Opus 4.8

![Claude Opus 4.8](claude/claude-opus-4.8/opus-4.8-max.jpg)

#### Claude Sonnet 5

![Claude Sonnet 5](claude/claude-sonnet-5/sonnet-5-max.png)

### DeepSeek

#### DeepSeek V4 Flash

![DeepSeek V4 Flash](DeepSeek/deepseek-v4-flash/pelican-bicycle.svg)

#### DeepSeek V4 Pro

![DeepSeek V4 Pro](DeepSeek/deepseek-v4-pro/pelican-bicycle.svg)

### Z.ai

#### GLM-5.2

![GLM-5.2](GLM/glm-5.2/glm-5.2-max.jpg)

#### GLM-5.3

![GLM-5.3](GLM/glm-5.3/glm-5.3-max.svg)

### OpenAI

#### GPT-5.5（xhigh）

![GPT-5.5](GPT/gpt-5.5/gpt-5.5-pelican-xhigh.png)

#### GPT-5.6 Luna

high：

![GPT-5.6 Luna high](GPT/gpt-5.6-luna/high/high.png)

xhigh：

![GPT-5.6 Luna xhigh](GPT/gpt-5.6-luna/xhigh/xhigh.png)

max：

![GPT-5.6 Luna max](GPT/gpt-5.6-luna/max/max.png)

#### GPT-5.6 Sol

high：

![GPT-5.6 Sol high](GPT/gpt-5.6-sol/high/high.png)

xhigh：

![GPT-5.6 Sol xhigh](GPT/gpt-5.6-sol/xhigh/xhigh.png)

max：

![GPT-5.6 Sol max](GPT/gpt-5.6-sol/max/max.png)

#### GPT-5.6 Terra

high：

![GPT-5.6 Terra high](GPT/gpt-5.6-terra/high/5.6-terra-high.png)

xhigh：

![GPT-5.6 Terra xhigh](GPT/gpt-5.6-terra/xhigh/5.6-terra-xhigh.png)

max：

![GPT-5.6 Terra max](GPT/gpt-5.6-terra/max/5.6-terra-max.png)

### Moonshot

#### Kimi K3

![Kimi K3](Kimi/kimi-k3/kimi-3-pelican.jpg)

### Meta

#### Muse Spark 1.2

![Muse Spark 1.2](meta/muse-spark-1.2/pelican_bicycle.svg)

### Alibaba

#### Qwen 3.8 27B

![Qwen 3.8 27B](Qwen/Qwen-3.8-27B/qwen-thinking-bicycle-27b.jpg)

#### Qwen 3.8 Max

![Qwen 3.8 Max](Qwen/Qwen-3.8-Max/qwen-3.8-max-pelican.png)

### Xiaomi

#### MiMo v2.5 Pro

![MiMo v2.5 Pro](xiaomi/mimo-v2.5-pro/pelican-on-bike.svg)
