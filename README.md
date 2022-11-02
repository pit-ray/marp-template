# marp-template
My marp style templates.


## Installation

### Windows
#### Scoop
```powershell
$ Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
$ irm get.scoop.sh | iex
```

#### Marp
```powershell
$ scoop install marp
```



## Compiling

#### To PDF
```powershell
$ marp --theme notosans-navy index.md -o output.pdf
```

#### To PowerPoint
```powershell
$ marp --theme notosans-navy index.md -o output.pptx
```
