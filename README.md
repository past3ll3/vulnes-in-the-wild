# vulnes-in-the-wild

# Windows

1) Abuse macros from Office to pop shell (VBArun-PE)
- https://github.com/itm4n/VBA-RunPE
2) Active Directory Powershell module (allow query to AD)
- Get-Module ActiveDirectory -ListAvailable 
3) Bypass Module adding
- $env:PSModulePath += ";C:\Users\blablabla"
