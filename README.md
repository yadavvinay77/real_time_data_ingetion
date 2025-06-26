# 🛰️ Real-Time EURUSD Streamer with MetaTrader5 + Kafka

![CI](https://github.com/yourusername/real-time-mt5-kafka/actions/workflows/python-ci.yml/badge.svg)

This project streams **real-time tick data** (e.g., `EURUSD`) from **MetaTrader 5** directly into **Apache Kafka** for downstream processing, analytics, or dashboarding.

---

## 🚀 Features

- Connects to MT5 demo/live accounts
- Streams tick data into a Kafka topic
- JSON serialization compatible with Spark / Flink / MongoDB
- Kafka topic: `market-data-topic`
- Easily extensible for OHLC / Candle data

---

## 📂 Project Structure

```bash
.
├── producer.py         # Main script
├── requirements.txt    # Python dependencies
├── README.md
└── .github/workflows   # GitHub CI/CD pipeline




---
💡 Contributors
Vinaykumar Yadav
📧 yadavvinay77@gmail.com

## 📈 Real-Time 1-Min Candle Chart (OHLC)

Yes, we can enhance your project to show **real-time candle charts** using:

- **`streamlit`** for real-time dashboard
- **`plotly`** for dynamic candlestick chart
- **Kafka consumer** to read from topic and update OHLC data

Let me know if you'd like me to:

- Build this Streamlit + Kafka consumer module for OHLC chart
- Or Dockerize the whole thing for easier deployment

