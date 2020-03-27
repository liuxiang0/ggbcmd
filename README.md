# ggbcmd
Search GGB - GeoGebra commands between English and Chinese, support non-greedy  match
模糊查询GGB指令集，可以通过英文查中文指令，也可以通过中文查英文指令。

Usage： gcmd  <searched_string> -- 通过输入的指令字符（中英文都可以）查询关联指令，含中英文指令
Example： gcmd point -- 查询含有p,o,i,n,t的指令
          gcmd Point -- 查询含有P,o,i,n,t的指令（大小写敏感）
          gcmd 点 -- 查询含有‘点’的指令
        
## 文件说明

ggbcmd.py -- main program
ggbcmd.spec -- specification for pyinstaller
LICENSE -- MIT license
README.md -- This file

## PyInstaller -- build executive program 

pyinstaller --clean ggbcmd.spec

