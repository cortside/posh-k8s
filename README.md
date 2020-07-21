# posh-k8s
Powershelp helpers for k8s

To install:
* Install-Module -Name InstallModuleFromGitHub
* Install-ModuleFromGitHub -GitHubRepo cortside/posh-k8s -Verbose
* Import-Module posh-k8s

To setup in your profile:
* notepad $PROFILE
* Add the following to your profile script:
```powershell
Install-ModuleFromGitHub -GitHubRepo cortside/posh-k8s -Verbose
Import-Module posh-k8s
```

Remember to reopen your shell.
