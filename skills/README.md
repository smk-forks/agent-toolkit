# Skills 技能目錄

本目錄收錄所有可用的 Agent Skills，每個子目錄包含一個獨立技能。

| 目錄名稱 | 技能簡述 | 技能說明 |
|----------|----------|----------|
| `agent-md-refactor` | Agent 指令檔案重構 | 將臃腫的 AGENTS.md、CLAUDE.md 等 Agent 指令檔案依漸進式揭露原則重構，將根檔案保持精簡並拆分為有結構的連結子檔案，避免指令矛盾與冗餘。 |
| `backend-to-frontend-handoff` | 後端 API 交接文件產生 | 後端開發完成後，自動產出供前端開發者（或其 AI）使用的結構化 API 交接文件，包含端點說明、資料模型、驗證規則與整合注意事項。 |
| `c4-architecture` | C4 架構圖產生 | 使用 C4 模型依 Mermaid 語法產生系統架構文件，支援 Context、Container、Component、Deployment 與 Dynamic 五個層級圖，適合各類受眾的架構說明。 |
| `codex` | Codex CLI 執行 | 透過 Codex CLI（GPT-5.2）進行程式碼分析、重構與自動編輯，支援唯讀、工作區寫入及完整存取三種沙箱模式，並可恢復先前的 Codex 工作階段。 |
| `command-creator` | Slash Command 建立 | 引導使用者建立 Claude Code slash commands（`/command-name`），涵蓋位置選擇、命令模式設計、參數定義與最佳化指令內容產生。 |
| `commit-work` | 高品質 Git Commit | 協助審查變更、分割邏輯提交範圍、撰寫符合 Conventional Commits 規範的提交訊息，確保僅提交預期變更並通過最小驗證。 |
| `crafting-effective-readmes` | README 撰寫與改善 | 根據專案類型（開源、個人、內部、設定）提供對應的 README 模板與撰寫指引，協助建立清楚說明專案目的與使用方式的文件。 |
| `daily-meeting-update` | 每日站會更新產生 | 互動式每日站會更新產生器，透過四個問題訪談（昨日、今日、阻礙、討論議題），並可整合 GitHub、Jira 與 Claude Code 歷程，輸出格式化 Markdown 更新。 |
| `database-schema-designer` | 資料庫 Schema 設計 | 設計生產就緒的 SQL/NoSQL 資料庫結構，涵蓋正規化、索引策略、外鍵約束、遷移腳本與效能最佳化，確保資料完整性與可維護性。 |
| `datadog-cli` | Datadog CLI 操作 | 透過 Datadog CLI 搜尋日誌、查詢指標、追蹤分散式請求及管理儀表板，提供完整的線上問題排查與事件分類工作流程。 |
| `dependency-updater` | 套件相依更新管理 | 自動偵測專案類型（Node、Python、Go、Rust、Ruby、Java、.NET），安全套用 Minor/Patch 更新，對 Major 版本逐一詢問確認，並執行安全性稽核。 |
| `design-system-starter` | 設計系統建立 | 建立包含設計 Token（色彩、排版、間距）、原子設計元件架構、深色模式主題、WCAG 2.1 無障礙規範與元件文件範本的完整設計系統。 |
| `difficult-workplace-conversations` | 職場困難對話引導 | 提供準備—執行—追蹤三階段框架，協助處理績效問題、同儕衝突、敏感薪酬討論等職場困難對話，包含 SBI 模型與情緒管理指引。 |
| `domain-name-brainstormer` | 網域名稱腦力激盪 | 針對新專案或品牌產生創意網域名稱建議，並驗證跨多種 TLD（.com、.io、.dev、.ai）的可用性，提供命名策略分析與建議。 |
| `draw-io` | draw.io 圖表編輯 | 編輯 `.drawio` XML 格式的圖表檔案，包含字型設定、PNG 轉換、版面座標調整、AWS 圖示使用與元素對齊最佳實踐。 |
| `excalidraw` | Excalidraw 圖表委派 | 透過子 Agent 委派處理所有 Excalidraw 圖表操作（讀取、修改、建立、比較），避免主 Agent 直接讀取高 Token 消耗的 JSON 檔案造成上下文耗盡。 |
| `feedback-mastery` | 建設性回饋技巧 | 運用準備—執行—追蹤模型與 SBI（情境—行為—影響）回饋框架，引導難以開口的職場對話、績效反饋與衝突解決，含實際 SBI 範例。 |
| `frontend-to-backend-requirements` | 前端需求文件 | 協助前端開發者以「描述需求而非規定實作」的方式向後端溝通資料需求，產出結構化需求文件，促進健康的前後端協作對話。 |
| `game-changing-features` | 10x 產品機會探索 | 以創始人思維進行策略性產品分析，從大型、中型、小型三個尺度發掘能讓產品價值提升 10 倍的功能機會，並依影響力與可行性排序優先級。 |
| `gemini` | Gemini CLI 執行 | 透過 Gemini CLI（Gemini 3 Pro）進行大規模程式碼審查、架構計畫評估與超過 200k Token 的大型上下文處理，支援互動式與背景自動化兩種模式。 |
| `gepetto` | 多步驟實作計畫產生 | 整合研究、使用者訪談、規格合成、實作計畫、多 LLM 外部審查（Gemini + Codex）與章節拆分，產出完整的可執行實作文件集。 |
| `humanizer` | AI 寫作特徵移除 | 根據 Wikipedia「AI 寫作特徵」指南，識別並移除文本中的 AI 生成模式（誇大重要性、宣傳性語言、-ing 分析句型、em dash 過度使用等），使文字更自然真實。 |
| `jira` | Jira 自然語言操作 | 以自然語言與 Jira 互動，自動偵測 CLI 或 MCP 後端，支援查看、建立、更新、轉換工單狀態、查詢 Sprint 等操作，含安全確認機制。 |
| `lesson-learned` | 程式變更學習萃取 | 分析 Git 歷程中的程式碼變更，對應軟體工程原則，萃取出具體、有依據的學習洞察，以反思而非說教的方式呈現給開發者。 |
| `marp-slide` | Marp 簡報製作 | 建立專業 Marp 簡報，提供 7 種預設主題（default、minimal、colorful、dark、gradient、tech、business），支援圖片排版與模糊需求的自動主題推薦。 |
| `meme-factory` | 網路梗圖產生 | 使用免費 memegen.link API 產生梗圖，支援 100+ 熱門模板、自訂文字與尺寸設定，並提供文字型梗圖格式與情境使用建議。 |
| `mermaid-diagrams` | Mermaid 圖表建立 | 使用 Mermaid 語法建立各類軟體圖表，包含類別圖、序列圖、流程圖、ERD、C4 架構圖、狀態圖、Git 圖、甘特圖等，含最佳實踐與匯出說明。 |
| `mui` | Material-UI v7 模式 | 提供 MUI v7 元件使用模式，涵蓋 sx prop 樣式、主題整合、響應式設計、常用元件（Grid、Card、Dialog）與 MUI 特有 hooks 的最佳實踐。 |
| `naming-analyzer` | 命名品質分析 | 分析程式碼中的變數、函數、類別、API 端點等命名品質，識別不清楚、誤導性或不一致的命名，依語言慣例提供具體改善建議與報告。 |
| `openapi-to-typescript` | OpenAPI 轉 TypeScript | 將 OpenAPI 3.0 規格（JSON/YAML）轉換為 TypeScript 介面、型別、請求/回應型別及型別守衛（type guards），自動處理 $ref 參照解析。 |
| `perplexity` | Perplexity AI 搜尋 | 使用 Perplexity AI 進行網路搜尋與研究，提供工具選擇優先鏈（Context7 → Graphite MCP → Nx MCP → Perplexity），避免不當工具使用造成上下文浪費。 |
| `plugin-forge` | Claude Code Plugin 開發 | 建立與管理 Claude Code plugin，包含目錄結構、`plugin.json` 與 `marketplace.json` 清單設定、版本管理腳本，以及本地測試與發布工作流程。 |
| `professional-communication` | 專業技術溝通 | 為軟體開發者提供電子郵件、即時訊息、會議議程與技術/非技術受眾溝通框架，含 What-Why-How 結構、主動語態原則與行話簡化指南。 |
| `qa-test-planner` | QA 測試計畫產生 | 為 QA 工程師產生測試計畫、手動測試案例、迴歸測試套件與錯誤報告，支援 Figma MCP 整合進行設計與實作比對驗證。 |
| `react-dev` | React TypeScript 開發 | 提供 React 18/19 TypeScript 型別安全模式，涵蓋元件 props 型別、事件處理、hooks 型別、泛型元件、Server Components、Server Actions 與路由整合。 |
| `react-useeffect` | React useEffect 最佳實踐 | 說明何時應避免使用 useEffect（衍生狀態、用戶事件回應），以及更好的替代方案（useMemo、key prop、事件處理器），基於 React 官方文件。 |
| `reducing-entropy` | 程式碼熵值縮減 | 以「最少程式碼量」為核心目標，偏向刪除而非添加，評估每次變更的實際程式碼總量變化，防止不必要的抽象化與過度工程。 |
| `requirements-clarity` | 需求澄清 PRD 產生 | 透過 0-100 分的清晰度評分系統，以多輪結構化對話澄清模糊需求，待評分達 90+ 後自動產出完整 PRD 文件（含驗收條件與執行階段）。 |
| `session-handoff` | AI 工作階段交接文件 | 建立詳細的工作交接文件，讓新的 AI Agent 能無縫接續工作，支援交接文件驗證（含密鑰掃描）、新鮮度檢查與鏈式交接追蹤。 |
| `ship-learn-next` | 學習內容轉行動計畫 | 將學習內容（YouTube 字幕、文章、教程）轉化為 Ship-Learn-Next 循環計畫（交付→學習→下一步），以具體可執行的反覆練習取代被動學習。 |
| `skill-judge` | Skill 設計品質評估 | 依 8 個維度（知識增量、思維框架、反模式品質、規格合規性、漸進揭露、自由度校準、模式識別、實用性）對 SKILL.md 進行 120 分滿分評估。 |
| `web-to-markdown` | 網頁轉 Markdown | 透過本地 `web2md` CLI（Puppeteer + Readability）將網頁 URL 轉換為乾淨的 Markdown，支援 JS 渲染頁面、互動式登入驗證與批次處理。 |
| `writing-clearly-and-concisely` | 清晰簡潔寫作 | 應用 Strunk《英文寫作風格》原則（主動語態、正面陳述、具體語言、刪除冗字），並識別 AI 寫作模式（浮誇詞彙、宣傳形容詞、格式濫用）以提升文字品質。 |
