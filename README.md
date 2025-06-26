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

## 💡 Contributors

---

Vinaykumar Yadav
📧 yadavvinay77@gmail.com
