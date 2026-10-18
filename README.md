# LUMINA
LUMINA is a creative AI trading agents for Binance bStock.
LUMINA 是一套「能賺錢」的交易架構，靈感來自 Jane Street（據稱交易美國股票市場約 10% 份額，日成交量達數千億美元）。

### 系統組成與運作方式

- 4 個 GrokBot（Scout、Analyst、Journal、Quant）共用一台雲端電腦，透過檔案交接工作。
- 你作為人類 PM，負責最終批准。
- 使用 Alpaca 紙上交易帳戶（$100K 虛擬資金）測試。
- 典型流程：凌晨 5:30 Scout 掃描 → Analyst 發送簡報與 0–5 張委託單到手機 → 你批准 → 開盤後執行，並有自動停損與第 5 天平倉等保護。
- 強調先用回測證明 edge（有鎖定 holdout），再紙上交易累積 25–50 筆，最後才考慮小額實盤。程式碼決定什麼能進市場，AI 只能提議。

---

##  Key Features  

- Speed: Rapid execution for real-time responses.  
- Creativity: Unlock new dimensions of AI-generated solutions.  
- Scalability: Build small, scale big with modular, flexible architecture.  
- Seamless Integration: Connect with APIs, databases, and cloud platforms effortlessly.  

---

##  Getting Started  

### Prerequisites  
- Python 3.9+  
- pip for dependency management  
- Docker (optional, for containerized deployment)  

### Installation  

```bash
git clone https://github.com/your-username/lumina.git
cd lumina
pip install -r requirements.txt
