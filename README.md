# postgresql_design

привет! что такое сущность events? когда заполняли форму, этого не было

да и это касается не только этой сущнсти. половины описанных в форме сущностей нет, но зато появились новые, которые не понятно что означают. напишите ниже какой смысл несет каждая из сущностей

## Employees:
Сотдруники
## EmployeeProfiles:
Дополнительная информация о сотруднике (менее важная)
## Positions:
Должность сотрудника. Я еще подумаю насчет связи один к одному, так как не хочется для каждого человека создавать запись в таблице Positions
## Departments:
Отдел, где работают сотрудники
## Bonuses:
Виды наград за действия сотрудников
## Actons:
Действия сотрудников (для слежки)
## Events:
Мероприятия, где собираются много сотрудников (досуг, командировка и тп0)
## Projects:
Проекты, задания, над которыми работают несколько сотрудников
