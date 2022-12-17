# devops-netology
# changes
Будут проигнорированы:

1. Все файлы в директориях .terraform
2. Все файлы файлы/папки с названием .tfstate или .tfstate.{любой символ (кроме /)}
3. Файлы с названием crash.log или crash.{любой символ (кроме /)}.log
4. Файлы с названием любой символ (кроме /).tfvars или любой символ (кроме /).tfvars.json
5. Файлы override.tf, override.tf.json и файлы с названием типа {любой символ (кроме /)}_override.tf, {любой символ (кроме /)}_override.tf.json
6. Файлы .terraformrc, terraform.rc


