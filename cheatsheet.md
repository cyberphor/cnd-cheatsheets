## Logging

**Windows**  
Log Network Connections
```
auditpol.exe /set /subcategory:"Filtering Platform Connection" /success:enable
```