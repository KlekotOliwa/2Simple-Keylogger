# 2Simple-Keylogger
Simple keylogger written in C# which is ready for modifications. 

## How to use it?
Create new .NET Framework console project in Visual Studio, change email informations in SendMail() method and compile it. 

## How does it work?
Keylogger stores keystrokes in chosen directory and when it detects that user is logging off or shutting down system it sends file with saved keystrokes to chosen email.
