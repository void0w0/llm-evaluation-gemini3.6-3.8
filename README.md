# llm-evaluation-gemini3.6-3.8
Google Gemini APIを使った複数LLMモデル3.6-3.8の比較評価（応答時間・文字数・回答品質）

##Tech Stack 使用技術
- Python / Jupyter Notebook
- Google Gemini API

##Models Evaluated 評価モデル
- gemini-3.6-flash
- gemini-3.7-flash
- gemini-3.8-flash

## Evaluation Criteria 評価観点
- Response time (seconds) 応答時間（秒）
- Output length (characters) 文字数
- Answer quality (qualitative analysis) 回答の質（考察）
  
## Setup セットアップ
1. Get your API key from Google AI Studio /Google AI StudioでAPIキーを取得
2. Set environment variable: export GEMINI_API_KEY="your-api-key"/環境変数に設定：export GEMINI_API_KEY="your-api-key"
3. Launch Jupyter Notebook
