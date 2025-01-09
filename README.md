# Языки интернет-программирования
Репозиторий для публикации лекций и ссылок на задания по лабораторным/РК
# Текущая успеваемость
[Таблица с баллами и зачтенными лабораторными работами](https://docs.google.com/spreadsheets/d/1yq4Il4FEEb56BE6lCFqe185eTo_LNX0wSaxnB0qO9q4/edit?usp=sharing)
# Лабораторные
1. [Git & GitHub](https://github.com/ValeryBMSTU/web-1)
2. [HTML & CSS](https://github.com/ValeryBMSTU/web-2)
3. [Golang](https://github.com/ValeryBMSTU/web-3)
4. [JavaScript](https://github.com/ValeryBMSTU/web-4)
5. [Асинхронное программирование на Golang](https://github.com/ValeryBMSTU/web-5)
6. [Back-End разработка на Golang](https://github.com/ValeryBMSTU/web-6)
7. [Front-End разработка на JavaScript](https://github.com/ValeryBMSTU/web-7)
8. [Golang & PostgreSQL](https://github.com/ValeryBMSTU/web-8)
9. [Golang & Echo](https://github.com/ValeryBMSTU/web-9)
10. [Golang & Clean Architecture](https://github.com/ValeryBMSTU/web-10)
11. [Golang & JWT](https://github.com/ValeryBMSTU/web-11)
12. [ОС](https://docs.google.com/forms/d/1pWlku-Ywcy0EaKid3GFB4JqhfW0YjzTkUuZrPKCQLlk/edit)
# РК
1. [Шаблон для написания РК1](https://github.com/ValeryBMSTU/web-rk1)
2. [Шаблон для написания РК2](https://github.com/ValeryBMSTU/web-rk2)
# Лекции
см. файлы в данном репозитории
# Экзамен
|Группа|Консультация|Экзамен|
|-|-|-|
|ИУ6-31Б|16.01.2025 14:00 на кафедре|17.01.2025 9:00 в 304х|
|ИУ6-32Б|9.01.2025 14:00 в 804|10.01.2025 14:00 в 110х|
|ИУ6-33Б|13.01.2025 14:00 в 808|14.01.2025 9:00 в 205х|
## Демонстрационный билет №1
1. Что такое HTTP и для чего он используется?
2. Что выведет код ниже и почему?
```
package main

import "fmt"

func main() {
    a1 := make([]int, 0, 10)
    a1 = append(a1, []int{1, 2, 3, 4, 5}...)
    a2 := append(a1, 6)
    a3 := append(a1, 7)

    fmt.Println(a1, a2, a3)
}
```
## Демонстрационный билет №2
1. Что такое горутина? Как её остановить?
2. Что выведет код ниже и почему?
```
package main

import "fmt"

type Example struct {}
type MyInterface interface{}

func example1() MyInterface {
 var e *Example
 return e
}

func example2() MyInterface {
 return nil
}

func main() {
 fmt.Println(example1())
 fmt.Println(example2())
 fmt.Println(example1() == example2())
}
```
## Демонстрационный билет №3
1. Как сообщить компилятору Go, что данный тип реализует интерфейс?
2. Будет ли корректно работать программа ниже? Если нет, то как её можно исправить?
```
package main

import (
	"fmt"
)

func main() {
	for i := 0; i < 10; i++ {
		go func() {
			fmt.Printf("%v ", i)
		}()
	}
}
```
# Материалы
Курсы, которые помогут вам сделать первые 6 лабораторные:
1. курс по Git: https://learngitbranching.js.org/?locale=ru_RU
2. курс по HTML+CSS+JavaScript: https://stepik.org/course/82108/info
3. курс по Golang: https://stepik.org/course/54403/info

Для общего развития:
1. тренажер слепой 10-пальцевой печати: https://klava.org/delta/#eng_code_go
2. курс по Golang от преподавателя технопарка: https://stepik.org/course/187490/info
3. курс по Linux: https://stepik.org/course/73/syllabus

