# .github

買賣不FOMO：ETF買賣決策助理

目錄結構
├── github/
│   └── workflows/
│       └── ci.yml              # GitHub Actions 工作流程
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md

├── redash/
│   ├── queries/                # 匯出的查詢 JSON
│   ├── dashboards/             # 儀表板設定
│   └── connections.json        # 資料來源設定（去除敏感資訊）

├── dataflow/
│   ├── etl_jobs/               # Python 資料清理與轉換腳本
│   ├── dags/                   # 若用 Airflow，放 DAG 檔案
│   └── config/                 # 參數/設定檔 (YAML/JSON)

├── database/
│   ├── schema/                 # 建表 SQL
│   ├── migrations/             # 資料庫版本控管工具使用
│   ├── seeds/                  # 初始資料（CSV 或 SQL）
│   └── ERD.png                 # 資料模型圖

├── api/
│   ├── routes/                 # API 路由（例如 endpoints）
│   ├── models/                 # 資料模型（ORM/Pydantic）
│   ├── services/               # 商業邏輯
│   ├── app.py                  # 主程式
│   └── docs/                   # Swagger/OpenAPI 或 API 使用說明

├── crawler/
│   ├── scripts/                # 爬蟲主程式
│   ├── parsers/                # 解析 HTML/XML 的模組
│   ├── scheduler/              # 自動排程腳本或 cronjob
│   ├── log/                    # 爬蟲日誌
│   └── source_list.md          # 資料來源與更新頻率說明
