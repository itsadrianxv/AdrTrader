# BLLA Trading System

This project is a small, runnable low-latency trading system for futures simulation.

It includes a local exchange, trading clients, and a separate SimNow gateway. The system uses C++20, CMake, low-latency queues, market data, order handling, risk checks, and simple maker/taker strategies.

The local exchange supports repeatable testing. SimNow credentials belong in a local `.env` file and are never committed.
