![[Screenshot from 2023-12-30 15-00-08.png]]

## Основное применение: файлы конфигурации  

### • Самый компактный язык разметки  
### • Для создания файлов настроек  
### • Используется для описания классов, ресурсов и манифестов в API*  
### • Может хранить несколько объектов в одном файле (в отличие от JSON)  

https://yaml.org/  
https://github.com/yaml/pyyaml

### Десериализация  
##### Из файла: yaml.load(file), yaml.load_all(file)*  
##### Из строки: yaml.loads(str)  
### Сериализация  
##### В файл: yaml.dump  
##### В строку: yaml.dumps  
### Печать не-ascii символов, отступы  
##### allow_unicode=True, default_flow_style=False  

![[Pasted image 20231230150324.png]]
  
https://pyyaml.org/wiki/PyYAMLDocumentation