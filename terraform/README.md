##### Коротенко Александр


# devops-netology


## Каталог terraform


### Пояснения к файлу .gitignore

В нем описываются конкретные файлы или их шаблоны, которые Git будет игнорировать.

--------------------------------------------------
\
**/.terraform/ *  - локальные папки .terraform любой вложенности

*.tfstate  - файлы, с расширением .tfstate  
*.tfstate. *  - файлы, содержащие в своем названии .tfstate

crash.log  - файлы, с именем crash.log

*.tfvars  - файлы, содержащие небезопасную информацию, с расширением .tfvars 

override.tf  - файлы, относящиеся к локальным ресурсам, с названием override.tf  
override.tf.json  - те же файлы, с названием override.tf.json  
*_override.tf  - те же файлы, название которых заканчивается на _override.tf  
*_override.tf.json  - те же файлы, название которых заканчивается на _override.tf.json

.terraformrc  - файлы конфигурации, с расширением .terraformrc  
terraform.rc  - файлы конфигурации, с названием terraform.rc

---------------------------------------------------
