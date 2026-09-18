# Permissions

Esta carpeta contiene script de shell, permisos

## Script

- `0-iam_betty` Creo n script que cambie el usuario actual al usuario betty.

- `1-who_am_i` Escribe un script que imprima el nombre de usuario efectivo del usuario actual.

- `2-groups` Escribe un script que imprima todos los grupos de los que forma parte el usuario actual.

- `3-new_owner` Escribe un script que cambie el propietario del archivo hello al usuario betty.

- `4-empty` Escribe un script que cree un archivo vacío llamado hello.

- `5-execute` Escribe un script que añada permiso de ejecución al propietario del archivo hello.

- `6-multiple_permissions` Escribe un script que añada permiso de ejecución al propietario y al grupo del propietario, y permiso de lectura a otros usuarios, al archivo hello.

- `7-everybody` Escribe un script que añada permiso de ejecución al propietario, al grupo propietario y a los demás usuarios, al archivo hello

- `8-James_Bond` Escribe un script que establezca los permisos del archivo hello de la siguiente manera:

    -Propietario: sin permisos en absoluto
    -Grupo: sin permisos en absoluto
    -Otros usuarios: todos los permisos

- `9-John_Doe` Escribe un script que establezca el modo del archivo hello en esto:

    -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

