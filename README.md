## PySpark. Связь m2m, создание датафреймов, применение ф-ций join(), filter(), union()

### Реализация задачи:

В PySpark приложении датафреймами (pyspark.sql.DataFrame) заданы продукты, категории и их связи. 
Каждому продукту может соответствовать несколько категорий или ни одной. А каждой категории может соответствовать несколько продуктов или ни одного. 
Напишите метод на PySpark, который в одном датафрейме вернет все пары «Имя продукта – Имя категории» и имена всех продуктов, у которых нет категорий.