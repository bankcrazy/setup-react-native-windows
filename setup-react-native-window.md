#Setup React Native on Windows

## Requirements
  1. Windows 7+

##Prerequisites
  1. Node.js
  2. Python 2 

##Recommend if you not have prerequisites
  Download Chocolatey, a popular package manager for Windows. [here](https://chocolatey.org/install).
  
  Download with proxy: 
  1. open cmd.exe as Administrator
  2. type in the following command
  
  > @powershell -NoProfile -ExecutionPolicy Bypass -Command "[System.Net.WebRequest]::DefaultWebProxy.Credentials [System.Net.CredentialCache]::DefaultCredentials; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin
  
 After Chocolatey is install:
    make sure it is up and running, you may need to restart your command prompt i.e cmd.exe, powershell.exe
    type in the following command:
    
    >choco
  should output something like this: Chocolatey v.0.9.10.3
  this mean your installation is complete

To upgrade version:
  use following command line:

  >choco upgrade chocolatey
  ><br/>choco upgrade chocolatey -pre
  
    
##Getting Prerequisites

For Node.js
  > choco install nodejs.install
  
For Python 2
  > choco install python2
  
##Getting React Native

  open up Node.js command prompt and type in 
  >npm install -g react-native-cli

Testing React Native Installation:

Use the React Native command line tools to generate a new React Native project called "Test Project", then run react-native run-android inside the newly created folder.
  
    > react-native init AwesomeProject
    > cd AwesomeProject
    > react-native run-android
    
  
  


