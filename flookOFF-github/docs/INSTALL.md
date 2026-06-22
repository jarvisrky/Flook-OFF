# Install

## Temporary activation

Use this when you want flookOFF to behave like a terminal venv only for the current PowerShell window:

```powershell
. .\activate.ps1
flookOFF
```

Run this to remove the temporary command and prompt marker:

```powershell
deactivate-flookOFF
```

## Persistent command

From the repo folder:

```powershell
powershell.exe -ExecutionPolicy Bypass -File .\install.ps1
```

Open a new PowerShell window and run:

```powershell
flookOFF
```

## Uninstall

```powershell
powershell.exe -ExecutionPolicy Bypass -File .\uninstall.ps1
```
