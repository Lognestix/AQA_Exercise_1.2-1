## `Статус сборки` [![Build status](https://ci.appveyor.com/api/projects/status/m9jonwha9uhsdoi1?svg=true)](https://ci.appveyor.com/project/Lognestix/aqa-exercise-1-2-1)
# Тестирование API, CI (AQA_Exercise_1.2-1)
## Домашнее задание по курсу "Автоматизированное тестирование"
## Тема: «1.2. Тестирование API, CI», задание №1: «Настройка CI», задание №2: «JSON Schema»
- Применены инструменты:
	1. Задание №1 - CI AppVeyor, реализован - .appveyor.yml
	1. Задание №2:
		- Rest Assured;
		- Json Schema Validator.
- Тестируемая функциональность:
	1. Задание №1 - настройка CI AppVeyor, проверка корректной работы.
	1. Задание №2:
		- Включить проверку схемы (модифицировать существующий тест так, чтобы он проверял соответствие схеме);
		- Доработать схему (найти способ валидации значения поля на два из возможных значения: "RUB" или "USD").
### Предварительные требования
- На компьютере пользователя должна быть установлена:
	- Intellij IDEA
### Установка и запуск
1. Склонировать проект на свой компьютер
	- открыть терминал
	- ввести команду 
		```
		git clone https://github.com/Lognestix/AQA_Exercise_1.2-1
		```
1. Открыть склонированный проект в Intellij IDEA
1. В Intellij IDEA перейти во вкладку Terminal (Alt+F12) и запустить SUT командой
	```
	java -jar artifacts/app-mbank.jar
	```
1. Запустить авто-тесты В Intellij IDEA во вкладке Terminal открыв еще одну сессию, ввести команду
	```
	./gradlew clean test
	```