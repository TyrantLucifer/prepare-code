prepare-code: A generate prepare code plugin for vim
===============================================

## 来源

原插件由chxuan开发，本插件在他基础上进行修改，增加在新建文件时自动插入作者信息

## 安装
    
- `vim-plug`

    Plug 'TyrantLucifer/prepare-code'

- `Vundle`

    Plugin 'TyrantLucifer/prepare-code'

## 使用

设置prepare-code插件的路径，读取预定义代码片段需要用到该路径，以下路径根据自己的实际情况进行配置。

    let g:prepare_code_plugin_path = expand($HOME . "/.vim/plugged/prepare-code")
    
## 特性

目前prepare-code支持以下语言:

- c/c++
- python
- bash
- Go


## License

This software is licensed under the [MIT license][1]. © 2020 TyrantLucifer


[1]: https://github.com/TyrantLucifer/prepare-code-plus/blob/master/LICENSE
