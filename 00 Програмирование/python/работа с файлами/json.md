### Формат JSON   

#### Основное применение: базы данных, выгрузки данных  

-  Для импорта/экспорта данных в базы данных (в т.ч. bson)
- Для сохранения вложенных структур данных
-  Также применяется при передаче данных клиент<->сервер для сериализации иерархических объектов
- Самый популярный и простой в использовании формат для Python и Java программистов
- Является подмножеством формата YAML
- Минусы -Нельзя читать файл частично, только полностью
https://docs.python.org/3/library/json.html документация JSON

### Десериализация  
##### Из файла: json.load(file)  
##### Из строки: json.loads(str)  
### Сериализация  
##### В файл: json.dump()  
##### В строку: json.dumps()  
### Печать не-ascii символов, отступы
##### ensure_ascii=False, indent=2

![[Screenshot from 2023-12-30 14-59-20.png]]