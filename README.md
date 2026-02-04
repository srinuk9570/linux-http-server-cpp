# Multithreaded HTTP Server (C++ / Linux)

A high-performance HTTP server built from scratch in C++ on Linux using socket programming and pthreads.

## Features
- Concurrent request handling using a custom thread pool
- TCP socket programming (POSIX)
- Efficient task queue to reduce latency
- Debugged and optimized using Valgrind and perf

## Tech Stack
- Language: C++
- OS: Linux
- Concurrency: pthreads
- Networking: TCP/IP sockets
- Tools: gdb, Valgrind, perf

## How to Build
```bash
make
