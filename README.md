# setup-scripts
Scripts I use to customize my windows install.

# Get the old right click context menu 

Run this command.

```reg.exe add "HKCU\Software\Classes\CLSID\{86ca1aa0-34aa-4e8b-a509-50c905bae2a2}\InprocServer32" /f /ve```

Reboot.
