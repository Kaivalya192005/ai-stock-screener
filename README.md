🚀 AI-Powered Mobile Stock Screener & Advisory Platform

An intelligent web-based stock analysis system that combines real-time market data, AI-based screening, semantic search, and alert notifications to help users analyze stocks efficiently.

Designed as a full-stack project demonstrating Backend, AI, and Data Engineering skills.

📌 Key Features

✅ Real-time stock price tracking
✅ Historical trend visualization
✅ AI-based stock screening
✅ Natural language stock queries
✅ Semantic search using vector embeddings
✅ Price alert system with notifications
✅ Portfolio & watchlist management
✅ Secure authentication using JWT

🧠 AI Capabilities

Semantic search using vector embeddings + FAISS

Natural language query understanding

Intelligent stock filtering

AI-driven recommendations (rule-based + data-driven)

🏗️ System Architecture

Client–Server architecture:

User → Frontend → Backend → AI / Database / APIs → Backend → Frontend

Components:

Frontend: UI, dashboards, charts

Backend (Flask): REST APIs, business logic

AI Layer: Semantic search engine

Database: PostgreSQL + CSV datasets

External APIs: Live market data providers

🛠️ Technology Stack
Layer	Technology
Frontend	HTML, CSS, JavaScript
Backend	Python, Flask
AI	Semantic Search, FAISS, Vector Embeddings
Database	PostgreSQL, CSV
APIs	Yahoo Finance, Alpha Vantage
Authentication	JWT
📡 API Endpoints
📊 Stocks
GET /api/stocks
GET /api/history/<symbol>

🤖 AI & Search
POST /api/ai-query
POST /api/semantic-search

🔔 Alerts
POST /api/alerts/create
GET /api/alerts/check
GET /api/alerts/intraday

🔐 Authentication
POST /api/signup
POST /api/login

🗄️ Database Design

Users — credentials & profiles

Alerts — price alert conditions

Portfolio — tracked investments

CSV datasets — historical stock data

🔐 Security Measures

✔ JWT-based authentication
✔ Environment variables for secrets
✔ .env file (not committed)
✔ .gitignore to protect sensitive data

⚙️ Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/Kaivalya192005/ai-stock-screener.git
cd ai-stock-screener

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Configure Environment Variables

Create .env file:

SECRET_KEY=your_secret_key
ALPHA_VANTAGE_KEY=your_api_key
DB_PASSWORD=your_db_password
EMAIL_ADDRESS=your_email
EMAIL_PASSWORD=your_app_password

4️⃣ Run Backend Server
python backend/app.py


Server runs on:

http://127.0.0.1:5000

🧪 Testing

Run test scripts:

python backend/test_data.py

⚠️ Constraints & Limitations
Technical

Depends on external market APIs

Requires stable internet connection

Data

Optimized for Indian stock market

CSV format must match schema

Security

Token-based authentication

Local session storage

🔮 Future Scope

🚀 Mobile application development
🚀 Advanced AI-based price prediction
🚀 Cloud deployment (AWS/GCP/Azure)
🚀 Support for global stock markets
🚀 Real-time streaming analytics

📜 License

This project is developed for educational and academic purposes only.
Not intended for real financial decision-making.

👨‍💻 Author

Kaivalya Agarkar
Computer Engineering Student
AI • Backend • Full-Stack Development

⚠️ Disclaimer

Stock data may not be fully accurate or real-time.
Always verify information from official financial sources before making investment decisions.
