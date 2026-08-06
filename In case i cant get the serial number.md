Open powershell and paste

```
Get-CimInstance Win32_BIOS | Select-Object -ExpandProperty SerialNumber
```
