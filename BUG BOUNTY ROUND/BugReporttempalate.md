# BUG REPORT TEMPLATE

| #  | Title                          | Severity | Component      | Description                                        | Repro Steps                                                  |
|----|--------------------------------|----------|----------------|----------------------------------------------------|--------------------------------------------------------------|
| 1  | IDOR on user profile           | High     | /api/user      | Accessing other users’ data via ID tampering       | 1. Login<br>2. Visit `/api/user?id=2`<br>3. View private data |