# Resume Project Summaries

## GitHub Profile Pin Descriptions

### IBirdy SaaS Commerce Operations API

ASP.NET Core SaaS backend prototype for commerce operations, including JWT auth, SQL Server persistence, EF Core/Dapper data access, Hangfire jobs, Swagger docs, order/product/inventory models, audit logs, and LINE/Facebook messaging integration.

### IBirdy Merchant Operations Console

Vue 3 SaaS operations console for merchant/admin workflows, covering product upload, orders, campaigns, billing, usage, audit logs, value-center pages, social commerce modules, Chrome extension support, and latest IBirdy auto-post toolkit.

### Electronic Invoice Value-Added Center

Node.js invoice platform prototype with REST APIs, multi-tenant operations flow, idempotent invoice creation, Turnkey-style async queue simulation, worker retries, signed webhook dispatcher, Docker setup, and operational documentation.

### JJ Auto Listing Publisher

Desktop automation prototype that reads Excel post plans, matches media folders, controls Chrome through Playwright/CDP, publishes scheduled Facebook group posts, writes status back to Excel, and packages diagnostics, launcher, installer, updater, and branch-store documentation.

### Legacy PHP Group-Buying System Python Port

Legacy modernization prototype that inventories a PHP group-buying/back-office system, maps PHP entry controllers into Python route metadata, preserves legacy assets, catalogs SQL dumps, and creates a runnable Python migration foundation.

## Resume Bullets

### IBirdy SaaS / Backend

- Built an ASP.NET Core SaaS backend prototype for commerce operations, covering orders, products, inventory logs, suppliers, campaigns, users, platform channels, and audit records.
- Implemented JWT authentication, Swagger API documentation, SQL Server persistence, EF Core/Dapper data access, and Hangfire scheduled jobs.
- Designed integration-ready service boundaries for LINE and Facebook messaging workflows.
- Modeled tenant-aware entities and backend controllers to support future multi-merchant SaaS expansion.

### IBirdy SaaS / Frontend And Auto-Listing

- Built a Vue 3 / Vite operations console with role-aware routing for admin, merchant, and customer workflows.
- Implemented dashboard, order, product upload, campaign, billing, usage, alert, audit, subscription, value-center, and merchant operation modules.
- Added social commerce surfaces for Facebook group/page/live, Instagram, LINE, and Plurk workflows.
- Packaged the latest IBirdy auto-post support kit with Chrome extension, Node native-host tooling, Playwright automation scripts, and customer-facing instructions.

### Electronic Invoice Value Center

- Built a Node.js electronic invoice platform prototype with API-first invoice creation, health checks, tenant-aware state management, and an operations console.
- Implemented idempotency controls, API-key access, Turnkey-style asynchronous queue simulation, worker retry handling, and dead-letter flow design.
- Created a signed webhook dispatcher using HMAC-SHA256 with retry behavior.
- Produced operational documentation, including API guide, webhook guide, monitoring notes, security baseline, backup runbook, release checklist, and migration plan.

### JJ Auto Listing Publisher

- Built a Playwright-based desktop automation tool that reads Excel post queues, maps rows to local media folders, publishes posts through Chrome, and writes status updates back to the workbook.
- Designed branch-store safeguards including batch limits, schedule slots, completed-row skipping, failed-row retry, manual-action detection, and sleep-prevention.
- Packaged the automation for non-technical users with a .NET launcher, installer, uninstaller, repair flow, auto-update manifest, and usage documentation.
- Added diagnostics including debug logs, failure screenshots, HTML captures, row/media context, and optional webhook failure reports.

### PHP To Python Port

- Created a first-stage migration foundation for a legacy PHP group-buying/back-office system with more than 100 application entry controllers.
- Scanned PHP controllers into structured Python route metadata, preserved legacy templates/static/language assets, and generated controller and schema catalogs.
- Built a runnable Python web foundation for incremental feature porting.
- Documented remaining manual migration areas including PHP business logic, template conversion, MySQL data access replacement, authentication, uploads, payment, invoice, LINE, and SMS integrations.

## Interview Version

### IBirdy Backend

這是一個 ASP.NET Core SaaS 後端原型，目標是把電商營運裡的訂單、商品、庫存、活動、供應商與社群訊息整合到同一個 API 平台。它有 JWT、SQL Server、EF Core、Dapper、Hangfire 排程與 Swagger。技術上展示了我做後端系統建模、API 設計、背景任務與外部訊息整合的能力。

### IBirdy Frontend And Auto-Listing

這是一個 Vue 3 商家營運後台，包含管理員、商家與客戶角色，還有商品上架、訂單、活動、帳務、用量、加值中心、稽核與多個社群平台模組。最新的 IBirdy 自動上架工具也被整理成前端可下載工具包與 Chrome/Playwright 支援流程，能展示我把 SaaS 操作介面和自動化工具整合在一起的能力。

### Electronic Invoice Value Center

這是一個電子發票加值中心的系統原型，我把需求拆成 API、Turnkey 類型非同步佇列、Worker、Webhook、租戶隔離、稽核紀錄與營運文件。重點是我不只做畫面，也把失敗重試、冪等、監控、資安、備份和送審資料這些真實營運會遇到的部分整理出來。

### JJ Auto Listing

這是一個給分店使用的桌面自動化工具，會讀 Excel、找對應圖片或影片資料夾，再透過 Playwright 控制 Chrome 到 Facebook 社團發文。它包含排程、批次限制、完成/失敗狀態回寫、失敗截圖、debug 紀錄、launcher、安裝與自動更新，適合展示我把內部流程做成可交付工具的能力。

### PHP To Python

這是一個舊 PHP 團購後台的現代化移植專案。第一階段不是硬翻每一行，而是先盤點 PHP 入口 controller、建立 Python route metadata、保留 legacy assets、整理 SQL schema catalog，並做出可以跑的 Python Web 骨架。這能展示我處理 legacy system、拆解遷移範圍和設計 incremental rewrite 的能力。

## Suggested Repository Name

`arille-operations-automation-portfolio`

## Suggested Topics

`portfolio`, `saas`, `operations-automation`, `aspnet-core`, `vue`, `nodejs`, `playwright`, `python`, `legacy-modernization`, `invoice`, `workflow-automation`

