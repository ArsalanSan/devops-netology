# devops-netology
file modofied

Согласно примеру: https://github.com/github/gitignore/blob/master/Terraform.gitignore.

**/.terraform/* - это означет к директории .terraform рекурсивно не будет применятся игнорирование,
но знак "*" говорит о том что исключить отслеживание всех файлов в текущей директории, при этом 
не распростроняется на поддиректории


*.tfstate - исключить все файлы с расширением .tfstate

*.tfstate.* - исключить все файлы любоенаименованиефайла.tfstate.любоерасширение


crash.log - не отслеживать файл crash.log

crash.*.log - исключить файл crash.любоенименование.log

add line for branch
