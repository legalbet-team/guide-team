Сущность
========

Сущность - это структура данных в виде объекта со свойствами и методами.
Сущность можно выбрать из хранилища, изменить ее свойства 
и передать хранилищу для сохранения или удаления.
По умолчанию, в сущности можно читать и изменять любой атрибут.
Так же можно сделать атрибут только для чтения или только для записи, 
есть возможность генерировать виртуальный атрибут.

## Цель

* Обеспечить структуру данных в виде объекта.
* Предоставить методы для манипуляции с атрибутами.
* Абстрагироваться от формата хранения.
* скрыть некоторые данные
* валидировать данные

## Особенности

* Хранилище - это контейнер для данных.
* Сущность может содержать вложенную сущность или коллекцию сущностей