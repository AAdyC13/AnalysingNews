# Analysing News (ANANews)
Collage project: python Django project - Analysing News (ANANews)

大學作品：自動新聞爬蟲 & AI分析網站

Information
---
This project uses Django and HTML5 to implement a responsive frontend design, deploys the website via Docker, utilizes Nginx for reverse proxy, manages distributed tasks with Celery and Redis, and integrates a self-trained LLM.

本專案使用 Django 與 HTML5 實現前端響應式設計，網站透過 Docker 部署，Nginx 做反向代理，Celery + Redis 管理分布式任務，並整合自訓 LLM。

## 🔑 API Key Setup

To use this project, you must provide your own [OpenAI API token](https://platform.openai.com/account/api-keys).

Create a file named `keys.json` in the **root directory** with the following structure:

```json
{
 "OPENAI_API_KEY": "",
 "OPENAI_ORG_ID": "",
}
