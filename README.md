![alt text](https://raw.githubusercontent.com/bobby-tablez/Windows-Sandbox-Flare-VM/main/sandbox_flare.png)

# Windows Sandbox - Flare VM
This config file will automatically convert a temporary Windows Sandbox environment into a Flare VM for malware analysis. Useful for standing up a "quick" flare-vm test environment on the fly. Additionally, enhanced logging telemetry is also enabled on the host. This is done by invoking https://github.com/bobby-tablez/Enable-All-The-Logs just before kicking off the flare-vm install. 

## Instructions
Install WSB (Windows Sandbox) and ensure all prerequisites are met:
https://learn.microsoft.com/en-us/windows/security/threat-protection/windows-sandbox/windows-sandbox-overview

Simply save this config (modify as neccissary) and be sure to preserve the ".wsb" extension. 

Execute the .wsb file and a new sandbox VM will spawn and the script to install FlareVM will auto-execute. This can take some time so grab a coffee!


## About Flare-VM
Flare VM is a Windows virtual environment created by Mandiant and is a collection of software installations scripts for Windows systems that allows you to easily setup and maintain a reverse engineering environment on a virtual machine (VM).
https://github.com/mandiant/flare-vm

Disclaimer: Use at your own risk
