# Anything Analyzer v3.6.33

## 修复

- **流式空文本响应诊断** — 避免流式响应完成但没有输出文本时被误判为空成功结果
  - OpenAI Chat、Responses API、Anthropic/MiniMax 流式解析现在都会在空文本结果时抛出明确格式错误
  - 新增回归测试覆盖三个流式接口只完成、不输出文本的异常路径

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.33.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.33-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.33-x64.dmg |
| Linux | Anything-Analyzer-3.6.33.AppImage |
