# Real-time-cryptocurrency-market-data-processing-system-built-with-Go-PostgreSQL-and-Redis.
Real-time cryptocurrency market data processing system built with Go, PostgreSQL, and Redis.

### This project simulates a backend for financial systems that:

    Ingests price updates from multiple exchanges (Live/Test mode)

    Processes data using Go concurrency patterns (worker pool, fan-in/out)

    Caches recent prices in Redis

    Aggregates and stores minute-based stats in PostgreSQL

    Exposes a REST API for querying price data and system status

### Features

    Hexagonal architecture

    Redis caching for fast access

    PostgreSQL for historical data

    Real/live and test data modes

    Graceful shutdown & logging

    Docker + Docker Compose setup

### Run
```
docker-compose up --build
```
