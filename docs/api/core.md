# 核心能力

## `POST /v1/chat`

用于发送对话请求。

### 请求示例

```json
{
  "model": "example-model",
  "messages": [
    {
      "role": "user",
      "content": "Hello"
    }
  ]
}
```

### 响应示例

```json
{
  "id": "resp_123",
  "output_text": "Hello"
}
```
