# marp-template
My marp style templates.


## Installation

### Windows
#### Install Scoop
```powershell
$ Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
$ irm get.scoop.sh | iex
```

#### Install Marp
```powershell
$ scoop install marp
```



## Compiling

### To PDF
```powershell
$ marp --theme notosans-navy index.md -o output.pdf
```

### To PowerPoint
```powershell
$ marp --theme notosans-navy index.md -o output.pptx
```
