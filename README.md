# Seedream 5.0 Pro API 中文文档（seedream-5.0 / seedream5.0）

> 按量计费，$1 起充，OpenAI 兼容接口。 **1K-layer $0.0146; 1K $0.0293; 2K-layer $0.0293**

**[模型页](https://apimart.ai/model) · [实时价格](https://apimart.ai/pricing) · [获取 API Key](https://apimart.ai/keys)**

## 价格（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `1K-layer` | $0.0146 |
| `1K` | $0.0293 |
| `2K-layer` | $0.0293 |
| `default` | $0.036 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/images/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"seedream-5-0-pro","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

本仓为第三方中转服务 APIMart 的接入说明，与模型提供方无隶属关系；价格以标注快照为准。
