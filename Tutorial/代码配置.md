# 代码配置

提出您的第一个请求
使用 Faraday API 就像在终端上进行 API 调用一样简单。

```
curl https://faraday.cloud/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer <API_KEY>" \
  -d '{
  "model": "gpt-4o",
  "messages": [
    {
      "role": "user",
      "content": "Hello world!"
    }
  ],
  "temperature": 1
}'
```

在“model”：“gpt-4o”部分，只需将“gpt-4o”替换为任何 Faraday AI 支持的模型的名称，即可直接轻松地进行 API 调用。
有关支持的型号和命名格式的列表，请查看“支持模型”。
