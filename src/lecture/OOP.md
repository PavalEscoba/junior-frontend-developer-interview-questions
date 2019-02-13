# ООП

- ООП - Объе́ктно-ориенти́рованное программи́рование - методология программирования, согласного которого программа представляется в виде объектов и их взаимодействий между собой. При этом объекты описываются соответствующими им классами. Которые в свою очередь образуют иерархию наследования.

- Класс - Определяет характеристики объекта. Класс является описанием шаблона свойств и методов объекта.
- Объект - Экземпляр класса и\или некоторая сущность в компьютерном пространстве,  обладающая определённым состоянием и поведением, имеющая заданные значения свойств (атрибутов) и операций над ними (методов)

3 основополагающих принципа ООП:
    - Наследование - принцип который предполагает создание новых(дочерних) классов на основе уже существующих(родительских). При этом класс наследник может в заимствовать частично или полностью функционал родительского класса (свойства и метода родительского и дополнительно свои, специфичные только для него).
    - Полиморфизм - один интерфейс - множество реализаций. Такое определение подходит для классических языков программирования, где одну ф-цию можно определить несколько раз для различного числа параметров. При этом получится что одна и тоже ф-ция работает для различного набора аргументов.
    - Инкапсуляция - отделение внешнего (пользовательского) логику от деталей внутренней реализации. Необходимо для того что бы пользователь не "знал" о внутренней реализации что бы не нарушить логику программы. Работает по принципу "черного ящика". Достигается использованием приватных методов и свойств, get/set и т.д.

Больше информации:

- [ООП с примерами (C#)][oop-habr-example]
- [Змейка через ООП (С#)][oop-habr-snake]
- [Серия статей ООП с примерами (часть 1)][oop-habr-series]

[oop-habr-snake]: https://habr.com/company/geekbrains/blog/268741/
[oop-habr-series]: https://habr.com/post/87119/
[oop-habr-example]: https://habr.com/post/87119/