## .gitignore для Terraform

`terraform/.gitignore`:

.terraform/
*.tfstate
*.tfstate.backup
*.tfvars
*.tfvars.json
crash.log
override.tf
override.tf.json
*_override.tf
*_override.tf.json

Благодаря  указанным правилам будут игнорироваться:

  Все файлы и каталоги с именем .terraform в любой директории (например, ./.terraform/, subdir/.terraform/).
  Все файлы с расширением .tfstate (например, state.tfstate, prod.tfstate).
  Все файлы с именем, заканчивающимся на .tfstate.backup (например, main.tfstate.backup).
    Все файлы с расширением .tfvars (например, secrets.tfvars, config.tfvars).
    Все файлы с расширением .tfvars.json.
    Файлы с именами override.tf, override.tf.json, а также любые файлы, имя которых заканчивается на _override.tf или _override.tf.json (например, prod_override.tf).


Edited via PyCharm!
