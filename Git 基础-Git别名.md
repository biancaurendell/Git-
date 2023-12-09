# Git 基础-Git别名

Git并不会在你输入部分命令时自动推断出你想要的命令。如果不想每次都输入完整的Git命令，可以通过git config文件来轻松地为灭一个命令设置一个别名。

```console
$ git config --global alias.co checkout
$ git config --global alias.br branch
$ git config --global alias.ci commit
$ git config --global alias.st status
```