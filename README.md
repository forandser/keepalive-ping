# keepalive-ping

Pings a private internal site's `/api/health` endpoint (returns only `{"ok":true}`, no data)
every 4 minutes during Korean business hours to prevent the free-tier database from suspending.
No secrets, no data — just an uptime ping.
