# Analysing News (ANANews)
日本語｜大学プロジェクト：自動ニュースクローラー・AI分析サイト  
English｜Collage project: Analysing News
中文｜大學作品：自動新聞爬蟲 & AI分析網站  

## プロジェクト紹介
### 使用言語・技術
- **プロジェクト**：一人単独で、「自動ニュースクローラー・AI分析サイト」を開発した。
- **技術スタック**：言語 `Python`、フレームワーク `Django`
- **開発期間與役割**：約6カ月。ニーズ定義からクローラー構築、AIロジック、フロントエンドまでの全ての作業を担当した。

### 工夫点
- **高速化と品質維持**：タイムリーに高信憑性を維持するため、**非同期処理（Asynchronous Processing）**によるクローリングの高速化と、重複記事の除外ロジックに工夫した。
- **UI/UXの改善**：バックエンドだけでなく、AIの分析結果（感情分析やキーワード抽出等）をユーザーが直感的に理解できるよう、フロントエンドのWebページにおける**UI（ユーザーインターフェース）の美化・改善**にも注力した。

## Information  
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
