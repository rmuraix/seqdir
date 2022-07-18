# seqdir
![License:MIT License](https://img.shields.io/github/license/rmuraix/seqdir)
![issues](https://img.shields.io/github/issues/rmuraix/seqdir)
[![DeepSource](https://deepsource.io/gh/rmuraix/seqdir.svg/?label=active+issues&show_trend=true&token=jqTF1fH8YMSsqfc0-yz4B4hG)](https://deepsource.io/gh/rmuraix/seqdir/?ref=repository-badge)
[![CodeFactor](https://www.codefactor.io/repository/github/rmuraix/seqdir/badge)](https://www.codefactor.io/repository/github/rmuraix/seqdir)   
simple command for Bash.
## Features
- Create sequential folders
## Download/Usage
1. Download [here](https://github.com/rmuraix/seqdir/releases).   
2. Execute command.  
```powershell
# format
$ seqdir <Number of folders to create(require)> <folder name> <division character>
# example
$ seqdir 10 hello _ # output: 01_hello, 02_hello, ... 10_hello
$ seqdir 2 hello # output: 1hello, 2hello
```
### Supported Bash Versions
| Version   | Supported          |
| :-------: | :----------------: |
| >=4.x     | :white_check_mark: |
| <=3.x     | :x:                |  

## Contributing  
Issues and PR are welcome. Please read [CONTRIBUTING.md](/CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](/CODE_OF_CONDUCT.md).    
## License
`rmuraix/seqdir` is under [MIT License](/LICENSE).