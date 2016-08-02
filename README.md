#Setup React Native on Windows

## Requirements
  1. Windows 7+

##Prerequisites
  1. Node.js
  2. Python 2 

If you not have these two prerequisites:
  I recommend you to download Chocolatey, a popular package manager for Windows. [here](https://chocolatey.org/install).
  
  Download Chocolatey with proxy: 
  
    - open cmd.exe as Administrator
    - type in the following command
    
    @powershell -NoProfile -ExecutionPolicy Bypass -Command "[System.Net.WebRequest]::DefaultWebProxy.Credentials = [System.Net.CredentialCache]::DefaultCredentials; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin
  
 After Chocolatey is install:
    make sure it is up and running, you may need to restart your command prompt i.e cmd.exe, powershell.exe
    type in the following command:
    
    choco
    
  
