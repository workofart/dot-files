# Frequently Forgotten Tips (FFT)

## Python

setup.py is a python file, which usually tells you that the module/package you are about to install has been packaged and distributed with Distutils, which is the standard for distributing Python Modules.

`python setup.py install`


## Git
Remove from both the git repository and filesystem
```shell
git rm file1.txt
```

To remove only from the git repository, not the file system
```shell
git rm --cached file1.txt 
```

## Mac Mojave
```shell
sudo installer -pkg /Library/Developer/CommandLineTools/Packages/macOS_SDK_headers_for_macOS_10.14.pkg -target /
```
