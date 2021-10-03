# devops-netology

## Системы контроля версий

### .gitignore

`**/.terraform/*` - содержимое всех папок .terraform рекурсивно

`*.tfstate` и `*.tfstate.*` - все файлы во всех папках с расширением tfstate и tfstate.[любое расширение] (например test.tfstate и /src/test.tfstate.abc)

`crash.log` - файлы лога во всех папках

`*.tfvars` - все файлы расширением tfvars во всех папках

Все файлы, которые используются для локального переписывания ресурсов:

```
override.tf
override.tf.json
*_override.tf
*_override.tf.json
```

Все файлы которые используются для натсройки CLI

```
.terraformrc
terraform.rc
```
