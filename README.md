# Markdown・クリップボード・OCRノートデスク

markdown-clipboard-ocr-note-desk は Windowsで制作メモ、OCR、Markdown整理を行う個人制作者 向けの closed alpha プロダクトです。クリップボード、OCRテキスト、Markdown見出しをローカルで整理し、出力前に不足を検査する。

## Source

- PICKUP Rank: 44
- Domain / Idea No: WindowsApp / 2
- Repository: markdown-clipboard-ocr-note-desk
- 主な公開先: GitHub Release / BOOTH
- created_idea: `D:/AI/WindowsApp/created_idea_002_markdown-clipboard-ocr-note-desk`
- 同梱ZIP: `D:/AI/WindowsApp/created_idea_002_markdown-clipboard-ocr-note-desk/idea_002_markdown-clipboard-ocr-note-desk.zip`
- 開始時 README: 存在しない


## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- ui/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/markdown-clipboard-ocr-note-desk-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。

