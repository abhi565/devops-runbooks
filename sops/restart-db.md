---
title: Restart PostgreSQL Database
category: Database
tags: [postgresql, restart, database]
author: DevOps Team
updated: 2025-07-03
---

# Restart PostgreSQL Database

This runbook outlines the steps to restart the PostgreSQL service safely.

## 🧰 Prerequisites

- SSH access to the server
- `sudo` privileges
- PostgreSQL service name (commonly `postgresql` or `postgresql-13`, etc.)

## 🔁 Steps

1. **Connect to the Server**
   ```bash
   ssh user@db-server