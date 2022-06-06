# devops-netology
Repository for studying


# Описание .gitignore файла в каталоге terraform
При следующем коммите в соответствии с файлом .gitignore будет игнорироваться следующее:
1. Все файлы содержащиеся во всех каталогах и подкаталогах с именем ".terraform"
2. Все файлы с расширением ".tfstate", а также все файлы содержащие в имени ".tfstate."
3. Все файлы с именем "crash.log", а также все файлы содержащие"crash." в начале файла и ".log" в конце.
4. Все файлы с расширениями ".tfvars" и ".tfvars.json"
5. Все файлы с именами "override.tf" и "override.tf.json", а также файлы имена которых заканчиваются на "_override.tf" и "_override.tf.json"
6. Все файлы с именами ".terraformrc" и "terraform.rc"