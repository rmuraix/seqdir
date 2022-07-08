# seqdir
![License:MIT License](https://img.shields.io/github/license/rmuraix/seqdir)
![issues](https://img.shields.io/github/issues/rmuraix/seqdir)
[![Analysis](https://github.com/rmuraix/seqdir/actions/workflows/analysis.yml/badge.svg)](https://github.com/rmuraix/seqdir/actions/workflows/analysis.yml)  
simple commandlet for PowerShell
## Features
- Create sequential folders
## Download/Usage
1. Download [here](https://github.com/rmuraix/seqdir/releases).  
2. Place it like this: `C:users/<user>/Documents/PowerShell/Modules/seqdir/seqdir.psm1`.  
3. Execute command.  
```powershell
# format
$ seqdir <number> <text>
# example
$ seqdir 3 hello # output: 01hello, 02hello, 03hello
```
### Supported PowerShell Versions
| Version   | Supported          |
| :-------: | :----------------: |
| 7.x       | :white_check_mark: |
| 6.x       | :x:                |
| 5.1.x     | :white_check_mark: |
| 5.0.x     | :x:                |
| 4.x       | :x:                |
| 3.x       | :x:                |  

## Contributing  
Issues and PR are welcome. Please read [CONTRIBUTING.md](/CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](/CODE_OF_CONDUCT.md).    
## License
`rmuraix/seqdir` is under [MIT License](/LICENSE).