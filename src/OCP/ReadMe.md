Классы должны быть открыты для расширения,но закрыты для модификации.


Классы Bus и Car переопределяют метод calculateAllowedSpeed - это расширение Vehicle.
У класса Vehicle кроме полного конструктора есть методы setMaxSpeed, setType
которые нарушают закрытие от модификации.