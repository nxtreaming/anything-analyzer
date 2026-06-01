# Anything Analyzer v3.6.19

## 修复

- **Responses API incomplete 状态显式报错** — 修复 `status: "incomplete"` 和 `response.incomplete` SSE 被当作成功响应的问题
  - 非流式响应会携带 `incomplete_details.reason` 抛出明确错误
  - 流式响应遇到 `response.incomplete` 会停止并返回截断原因，避免误用部分输出

## 下载

| 平台 | 文件 |
|------|------|
| Windows | Anything-Analyzer-Setup-3.6.19.exe |
| macOS (Apple Silicon) | Anything-Analyzer-3.6.19-arm64.dmg |
| macOS (Intel) | Anything-Analyzer-3.6.19-x64.dmg |
| Linux | Anything-Analyzer-3.6.19.AppImage |
