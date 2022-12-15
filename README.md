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
$ marp --html --allow-local-files --theme notosans-navy.css index.md -o output.pdf
```

#### To PowerPoint
```powershell
$ marp --html --allow-local-files --theme notosans-navy.css index.md -o output.pptx
```
