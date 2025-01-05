# Redis Documentation

## Overview

**Redis** (Remote Dictionary Server) is an open-source, in-memory data structure store that can be used as a database, cache, and message broker. It supports various data structures such as strings, hashes, lists, sets, sorted sets, bitmaps, and more.

---

## Features

- **In-Memory Storage:** Redis stores data in memory for fast access.
- **Persistence:** Options for data persistence via RDB snapshots or AOF (Append Only File).
- **Data Structures:** Support for strings, lists, hashes, sets, and sorted sets.
- **Pub/Sub Messaging:** Publish/subscribe capabilities for real-time applications.
- **Cluster Support:** Scalability with Redis Cluster.
- **High Availability:** Automatic failover using Redis Sentinel.

---

## Common Commands

| Command                 | Description                           |
|-------------------------|---------------------------------------|
| `SET key value`         | Set a key with a specific value      |
| `GET key`               | Get the value of a key               |
| `DEL key`               | Delete a key                         |
| `KEYS pattern`          | List keys matching a pattern         |
| `EXPIRE key seconds`    | Set a key to expire after a time     |
| `LPUSH key value`       | Add value to the beginning of a list |
| `LRANGE key start stop` | Get a range of elements from a list  |


