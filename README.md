# TASCOM-Bridge-Release
TASCOM Bridge 프로그램 다운로드용 공개 repo

```
New-NetFirewallRule -DisplayName "TASCOM Bridge (TCP-In)" -Direction Inbound -LocalPort 33300 -Protocol TCP -Action Allow
New-NetFirewallRule -DisplayName "TASCOM Bridge (UDP-In)" -Direction Inbound -LocalPort 33300 -Protocol UDP -Action Allow
```
