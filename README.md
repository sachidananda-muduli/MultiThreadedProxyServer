# MultiThreadedProxyServer

# Proxy Server

## Overview

This project implements a multi-threaded HTTP proxy server in C that handles client requests and serves cached responses. It utilizes a simple cache mechanism with Least Recently Used (LRU) eviction policy, allowing efficient management of HTTP responses.

## Features

- **Multi-threading**: Supports multiple client requests simultaneously using POSIX threads.
- **Caching**: Implements an LRU cache to store HTTP responses for quick retrieval.
- **Error Handling**: Responds with appropriate HTTP status codes for different scenarios (e.g., 400 Bad Request, 404 Not Found).
- **Socket Programming**: Handles TCP connections for client-server communication.

## Getting Started

### Prerequisites

- A C compiler (GCC recommended)
- POSIX threads library
- Basic understanding of C and socket programming

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/proxy-server.git
   cd proxy-server
