# BLLA Trading System

This project turns the code from *Building Low-Latency Applications with C++* into a small, runnable trading system.

It includes the book's local exchange and trading client, plus a separate SimNow gateway for futures simulation. The system uses C++20, CMake, low-latency queues, market data, order handling, risk checks, and simple maker/taker strategies.

The local exchange is used to test the complete book example. SimNow credentials belong in a local `.env` file and are never committed.
