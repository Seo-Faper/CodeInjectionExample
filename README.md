# CodeInjectionExample
```
$url = "
https://github.com/Seo-Faper/CodeInjectionExample/raw/main/Release/CodeInjection2.exe"
$savePath = "C:\Windows\Temp\CodeInjection.exe"
$webClient = New-Object System.Net.WebClient
$webClient.DownloadFile($url, $savePath)
$webClient.Dispose()
```
