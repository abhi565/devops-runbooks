
---

### ✅ `login-issue-troubleshoot.md`

```markdown
---
title: Login Issue Troubleshooting
category: Authentication
tags: [login, auth, troubleshooting]
author: DevOps Team
updated: 2025-07-03
---

# Login Issue Troubleshooting

This runbook helps you diagnose and resolve login-related issues in the web application.

## 🧰 Prerequisites

- Access to logs and database
- User details (username/email)

## 🔁 Steps

1. **Identify the Error Message**
   - Ask user for screenshot or exact message.

2. **Check Application Logs**
   ```bash
   tail -f /opt/myapp/logs/auth.log
