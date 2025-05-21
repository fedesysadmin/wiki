# How to restore the old Context Menu in Windows 11

It is possible to restore the old context menu in Windows 11 OS.

Please follow steps reported below:

- Right-click the Start button and choose Windows Terminal (without Administrator privileges)

- Copy the command from below, paste it into Windows Terminal Window, and press enter.
>reg.exe add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve

- Restart File Explorer service for the changes to take effect or reboot your laptop
