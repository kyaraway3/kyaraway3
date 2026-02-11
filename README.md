# Hi, I'm Yuki 👋 Thank you for taking the time to read about me.

Python / PyTorch を中心に  
**実運用を想定した機械学習・画像処理システム・自然言語処理**を個人開発しています。

単にモデルを動かすだけでなく、  
**依存関係・実行環境・運用安定性**まで含めて設計することを重視しています。

リアルタイム映像処理・GPU 推論・現場運用を意識した構成に関心があります。

---

### Languages & Frameworks
- **Language**: Python 3.10, SQL, Google Apps Script
- **ML / DL**: PyTorch, Transformers (Hugging Face), Scikit-learn, LightGBM
- **LLM / Generative AI**: **Gemini 1.5 Flash (API Integration), Prompt Engineering**
- **CV / NLP**: OpenCV, BERT (v3)
- **API**: FastAPI, Uvicorn

### DevOps & Infrastructure
- **Cloud**: Google Cloud Platform (Cloud Run, Artifact Registry, Cloud Storage)
- **Container**: Docker (Environment Isolation, Optimized for CPU/GPU)
- **Tools**: Git/GitHub, CUDA (11.8/12.4), venv, RTSP, dotenv

---

## 📌 Featured Projects

### 🆕 🛡️ ScamWall: AI-Powered Hybrid Scam App Detection （Work In Progress（開発中））
**BERT モデルを用いた詐欺アプリ検知システム（自然言語処理）**

🔗 https://github.com/kyaraway3/scamwall

- **Hybrid AI Architecture**: 
  - 1次判定（高速スクリーニング）：**BERT** によるテキストベクトル分析。
  - 2次判定（高度推論）：**LLM (Gemini 1.5 Flash)** による文脈解析と「詐欺の根拠」の生成。
  - **Cost & Speed Optimization**: 判定難易度に応じた階層化推論により、APIコストの削減と低レイテンシを両立。
- **Cloud Native**: **Google Cloud Run** へデプロイし、サーバーレス環境での本番稼働を実現。
- **Status**: Backend API Completed ✅ / Android Client In Progress 🏗️
- **Highlights**: 
  - 自作データセットによる学習で **Accuracy 83.8%** を達成。
  - NumPy 2.x 競合などの依存関係トラブルを Docker 構成で解消し、再現可能なパイプラインを構築。
## 💼 Professional Background

- **Mathematics**: 大学にて数学（線形代数・常微分方程式）を専攻。統計的アプローチの基礎。
- **Mobile Industry (13 years)**: 携帯キャリアショップ運営に従事。現場の課題を Python/GAS で自動化し、年間200時間の工数削減を達成。この経験が「現場で使えるAI」へのこだわりの源泉です。
---

### 🎥 PyTorch RTSP Person Detection
**RTSP カメラ映像から人物をリアルタイム検知し、検知前後の映像を自動保存**

🔗 https://github.com/kyaraway3/pytorch-rtsp-person-detection

**Tech Stack**
- PyTorch (CUDA 11.8)
- OpenCV (RTSP capture)
- NumPy 1.26.4
- Python-dotenv

**Highlights**
- GPU メモリ枯渇を防ぐための推論間引き・`no_grad()`・`eval()` 制御
- RTSP バッファ管理による安定ストリーム処理
- NumPy / OpenCV / PyTorch の依存関係衝突を考慮した構成
- Docker 化を見送った理由を README に明記（再現性・安定性優先）

---

### ⚙️ Business Automation Portfolio
**業務効率化を目的とした Python 自動化・データ処理ツール群**

🔗 https://github.com/kyaraway3/portfolio

**Examples**
- Google Spreadsheet API 連携
- データ集計・自動通知処理
- 設定値・認証情報の外部化設計

---

## 🧠 What I Value in Development

- 動けばいい、では終わらせない
- **「なぜこの構成にしたか」を説明できるコード**
- 実運用・保守を前提とした設計
- 依存関係・実行環境の再現性

---

## 🎯 Interests

- Computer Vision
- Real-time video processing
- Practical ML system design
- Stable ML systems beyond PoC

---

## 📫 Contact

- GitHub: https://github.com/kyaraway3
