# 讓 agent 做完之後交得出手：Matt Pocock Skills v1.3 導讀

Matt Pocock 在影片 "New Skills! v1.3 brings /pr, /implement-spec, and /retro" 裡介紹 skills repo 的 v1.3：三個新 skill（`implement-spec`、`pr`、`retro`）與 `CONTEXT.md` 改名 `GLOSSARY.md`。這篇導讀依影片逐字稿與官方 repo（SKILL.md、release 說明）整理各自做什麼，並標出講者口述與官方文件不一致之處：implement-spec 的終點是 integration branch 而不一定是 PR；glossary 改名涵蓋 `CONTEXT-MAP.md`、檔名為大寫；講者說「沒有 1.3.0 release」，但官方列表同時有 v1.3.0 與 v1.3.1。另引用影片畫面中 André Staltz 對 `/retro` 的貼文。

## 200字介紹

Matt Pocock 讓新做的 /retro 去讀自己的 agent 工作紀錄，結果它抓到 agent 沒問就發了 release。他看完說無所謂，還要大家別把 retro 全自動，輕重留給人判斷。這支 v1.3 影片另介紹 implement-spec、pr 兩個新 skill 與 GLOSSARY.md 改名。導讀對照官方文件，標出他口述與官方不一致之處，例如 implement-spec 的終點不一定是 PR。

## 檔案

| 檔案 | 說明 |
|---|---|
| `index.html` | 單檔網頁，可直接用瀏覽器開啟；CSS 與互動全內嵌，圖片用本機相對路徑，無外部腳本 |
| `matt_pocock_skills_v1_3.md` | 正式 Markdown |
| `images/` | 頁首全覽圖、內文三張配圖（implement-spec、pr、retro，各 16:9／9:16，在 `figs/`）與分享封面 `hero/og_1200x630.png` 的 PNG 原檔；`images/web/` 是網頁實際載入的 WebP |
| `share_post.md` | 社群分享文 |
| `qa/`、`research/` | 驗收、審稿與查證紀錄、官方檔副本、提示詞與建置腳本，僅留作者本機，不公開 |

## 原始資料

- 類型：影片
- 名稱：New Skills! v1.3 brings /pr, /implement-spec, and /retro（Matt Pocock 頻道，2026-10-05，14:34）
- 網址：https://www.youtube.com/watch?v=BsJGo1wFTvQ
- 逐字稿：YouTube 自動字幕（400 段，有誤聽，已依官方資料與影片畫面校正），未隨 repo 附上

## 重要來源

- 官方（皆於 2026-10-05 讀取）：
  - [mattpocock/skills](https://github.com/mattpocock/skills)：[v1.3.0](https://github.com/mattpocock/skills/releases/tag/v1.3.0)（2026-10-04）、[v1.3.1](https://github.com/mattpocock/skills/releases/tag/v1.3.1)
  - [implement-spec/SKILL.md](https://github.com/mattpocock/skills/blob/main/skills/engineering/implement-spec/SKILL.md)、[pr/SKILL.md](https://github.com/mattpocock/skills/blob/main/skills/engineering/pr/SKILL.md)、[pr/CREDITS.md](https://github.com/mattpocock/skills/blob/main/skills/engineering/pr/CREDITS.md)、[retro/SKILL.md](https://github.com/mattpocock/skills/blob/main/skills/engineering/retro/SKILL.md)
  - 講者背景：[GitHub：mattpocock](https://github.com/mattpocock)（自述）
  - Lauren Tan 即 Poteto：[訪談影片](https://www.youtube.com/watch?v=MN9dGgmLyso)、[pstack 的 plugin.json](https://github.com/cursor/plugins/blob/main/pstack/.cursor-plugin/plugin.json)
- 取自影片畫面：André Staltz（@andrestaltz）2026-10-04 的貼文。未另在 X 上開啟原貼文。

## 重要限制

- 講者的觀察與效果（sub-agent 能力、`pr` 在 Opus 5.5 上似乎每次觸發、retro 讓品質提升）都是自述，沒有外部數據。
- 官方 repo 之後可能再變動，文中以 2026-10-05 的內容為準。
- 時間連結取自字幕檔，與播放位置可能略有出入。
- `Lauren` 在影片字幕中的相關句子（約 00:06:20）有一個字聽不確定，文中不引用該詞。
- `animatic` skill 位於講者另一個 repo，未讀到其 SKILL.md，文中只提名稱。
- 影片結尾推薦講者自己的 AI coding 課程，這是商業利益，文中已提醒。
- 圖片為 AI 生成的示意圖，文字已逐張目視確認，內容只用文章已有的資訊；9:16 版曾把「舊檔」畫成「舊議」，已重生。
- `og:url` 與 `og:image` 使用本頁正式網址 `https://lushinshang.github.io/matt_pocock_skills_v1_3/`，已隨本次發布生效；LINE 分享預覽未實測。

## 狀態

已發布（2026-10-05）。

- 網頁：https://lushinshang.github.io/matt_pocock_skills_v1_3/
- Repo：https://github.com/lushinshang/matt_pocock_skills_v1_3（公開，Pages 用 `main` 分支根目錄）
- 公開內容只有 `index.html`、`matt_pocock_skills_v1_3.md`、`README.md`、`share_post.md`、`images/`；`qa/` 與 `research/` 不公開。
- 公開版 Markdown 已移除 frontmatter 的 `local_path`。
