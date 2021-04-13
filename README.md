# Postman
О репозитории Postman
=====

В этот репозиторий я загрузила свои практические и домашние задания, которые выполняла во время обучения на курсах. 

- Папки с файлами **Tests_in_Pm_Europe** и **Tests_in_Pm_USA**.

В этом задании я разбила каждую возрастную группу на граничные значения и по классам эквивалентности. Написала простые тесты для проверки, что каждый введенный в запрос возраст соответствует возрасту в ответе, принадлежит своей возрастной группе и соответствует количеству предложенных фильмов.  

**Задание:** 
```
{"Server IP": "116.203.27.46",
 "Port": "5002",
 "Postman":[{"endpoint": "age_europe",
            "method": "POST",
            "body_params": "age: int",
            "age_class":["0-17", "18-50", "50-100"],
            "task": "Create equivalence classes and boundary values tests"}
            {"endpoint": "age_usa",
            "method": "POST",
            "body_params": "age: int",
            "age_class":["0-20", "21-50", "50-100"],
            "task": "Create equivalence classes and boundary values tests"}],
}
```
