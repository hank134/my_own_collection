# Ansible Collection - my_own_collection.eam
## Описание  
Коллекция копирует файл с заданным содержимым

## Переменные
| Переменная | описание | значение по умол
| :------------ | :------------------------------ | :--
test_path | имя файла который необходимо создать |./my_test_file.txt|
test_content| содержимое файла | Testing playbook content

## Пример
```
  - name: Test
    hosts: localhost
    roles:
      - my_own_role
```    