# Ruby Examples

## IDE

Visual Studio Code


## Installation

https://dev.to/dnamsons/ruby-debugging-in-vscode-3bkj

### Install Ruby

https://rubyinstaller.org/downloads/

### Install Gems

```
gem install ruby-debug-ide
gem install debase
```


## Debugging

### Configure launch.json

```
"name": "Debug Local File - Current",
"type": "Ruby",
"request": "launch",
"cwd": "${workspaceRoot}",
"program": "${file}"
```

