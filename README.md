ws_csharp_mp
===========

Sample C# Windows Service

## Installation ##

- Open the solution
- Rename App.config.default to App.config
- Update the log path values for log4net Appenders in App.config file
- Build the project
- Install the service using InstallUtil command
  - open the Developer Command Prompt
  - execute this command - installutil MP_WService.exe
- Uninstall the service
  - Open the Developer Command Prompt
  - execute this command - installutil /u MP_WService.exe
