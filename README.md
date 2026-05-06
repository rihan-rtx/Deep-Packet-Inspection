# Deep Packet Inspection (DPI) Engine

A C++ based Deep Packet Inspection (DPI) system for analyzing and filtering network traffic from PCAP files.

## Features
- Packet parsing (TCP/UDP/IP)
- SNI extraction from HTTPS traffic
- Application detection (YouTube, Facebook, Google, etc.)
- Rule-based blocking for apps, domains, and IPs
- Multi-threaded packet processing
- Traffic analytics generation

## Tech Stack
- C++
- Multi-threading
- Socket Programming
- PCAP Processing

## Build

```bash
g++ -std=c++17 -pthread -O2 -I include -o dpi_engine src/*.cpp
```

## Run

```bash
./dpi_engine test_dpi.pcap output.pcap
```

## Author
Rihan Baig
