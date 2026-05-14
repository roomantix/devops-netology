### Решение Задания - Создание файлов .gitignore и второго коммита


```
В файле /terraform/.gitignore
Описаны правила игнорирования для terraform, ниже описал , что конкретно делает 
каждое правило.

.terraform/
игнорирует папку с именем .terraform и всё её содержимое.
*.tfstate
Игнорирует все файлы с расширением .tfstate.
*.tfstate.*
Игнорирует ылюбые файлы, имя которых содержит .tfstate.

crash.log
Игнорирует файл с точным именем crash.log.
crash.*.log
Игнорирует файлы вида crash.значения.log

*.tfvars
Игнорирует все файлы с расширением .tfvars
*.tfvars.json
Игнорирует все файлы с расширением .tfvars.json

override.tf
Игнорирует файл с точным именем override.tf
override.tf.json
Игнорирует файл с именем override.tf.json
*_override.tf
Игнорирует любой файл, имя которого заканчивается на _override.tf
*_override.tf.json
Игнорирует файлы с суффиксом _override.tf.json

.terraform.tfstate.lock.info
Игнорирует файл с именем .terraform.tfstate.lock.info
.terraformrc
Игнорирует файл .terraformrc
terraform.rc
Игнорирует файл terraform.rc 

```
