# Hi, I'm Yuki 👋 Thank you for taking the time to read about me.

Python / PyTorch を中心に  
**実運用を想定した機械学習・画像処理システム**を個人開発しています。

単にモデルを動かすだけでなく、  
**依存関係・実行環境・運用安定性**まで含めて設計することを重視しています。

リアルタイム映像処理・GPU 推論・現場運用を意識した構成に関心があります。

---

## 🔧 Skills

- **Language**: Python 3.10
- **ML / CV**: PyTorch, TorchVision, OpenCV
- **Data**: NumPy, Pandas
- **Environment**: venv, CUDA (11.8)
- **Other**: RTSP, dotenv, GitHub

---

## 📌 Featured Projects

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
