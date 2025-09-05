# Redis Clone

A simplified Redis-like key-value store implemented in C++, built step by step by following the tutorial [Build Your Own Redis](https://build-your-own.org/redis/#table-of-contents).  

This project implements all features from **Step 3 to Step 14**, covering networking, event-driven I/O, data structures, and concurrency.

---

## Features Implemented

- **Step 3:** Basic TCP server and client communication  
- **Step 4:** Request–response protocol for command handling  
- **Step 5:** Concurrent I/O models with non-blocking sockets  
- **Step 6–7:** Event loop (basic + extended)  
- **Step 8:** Minimal key–value server (`GET`, `SET`)  
- **Step 9–10:** Hash table implementation (collision handling, resizing)  
- **Step 11:** Data serialization/deserialization  
- **Step 12:** Balanced binary tree  
- **Step 13:** Sorted sets built on trees  
- **Step 14:** Thread pool for concurrent task execution  

---

## Getting Started

```bash
# Clone the repo
git clone https://your-git-host/redis-clone.git
cd redis-clone

# Build any step (example: Step 09)
cd 09
make

# Run the server
./09_server

# Run the client (or use netcat/telnet)
./09_client
