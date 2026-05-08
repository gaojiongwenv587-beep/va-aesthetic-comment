# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| 1.x     | ✅        |

## Reporting a Vulnerability

如發現安全問題，請勿直接開 Issue，避免在修復前被利用。

請通過以下方式私下回報：

- **GitHub**: 使用 [Private Vulnerability Reporting](https://github.com/gaojiongwenv587-beep/va-aesthetic-comment/security/advisories/new)
- 收到回報後，我們將在 **72 小時內**確認並回覆修復計劃。

## Security Considerations

本 Skill 為純文字生成工具，不涉及網絡請求、瀏覽器操控或憑證存取，風險面較低。請注意：

- **無外部請求**：Skill 本身不發送任何網絡請求，所有内容均在本地 Claude Code 環境內生成
- **價格表為公開資訊**：`references/knowledge-base.md` 中的價格資料均為診所公開資訊，不含任何敏感數據
- **輸出審查**：生成的回覆草稿在貼到社群平台前，請自行審查確認符合平台規範

## Scope

安全回報適用範圍：

- ✅ Skill 文件中的惡意代碼注入風險
- ✅ 依賴項中的已知 CVE（如有）
- ❌ 生成內容的准確性或適切性（屬使用者責任）
- ❌ 社群平台封號風險（屬使用者使用方式責任）
