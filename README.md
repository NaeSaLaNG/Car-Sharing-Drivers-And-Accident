Введение

**Мне был поставлен важный заказ на создание системы, способной оценить риск дорожно-транспортных происшествий (ДТП) на основе выбранного маршрута движения**. Под риском понимается вероятность ДТП с любым уровнем повреждения транспортного средства. **Целью этого проекта является разработка системы**, которая будет активироваться, когда водитель забронирует автомобиль, сядет за руль и выберет маршрут, предоставляя предупреждения и рекомендации при высоком уровне риска.

Идея создания такой системы находится в стадии предварительного обсуждения, и на рынке пока не существует чёткого алгоритма работы или аналогичных решений. **Текущая задача состоит в исследовании возможности предсказания ДТП, опираясь на исторические данные одного из регионов**.

**Цели проекта**:

1. **Создание модели предсказания ДТП с фокусом на тип виновника "машина" (car) в таблице происшествий.**
2. **Выявление случаев, когда ДТП приводило к любым повреждениям транспортных средств, исключая тип SCRATCH (царапина).**
3. **Построение модели с использованием данных за 2012 год, обеспечивающих актуальность информации.**
4. **Учет фактора возраста автомобиля в модели, как важного параметра риска.**

**Ключевые вопросы исследования**:

1. **Возможно ли разработать адекватную систему оценки водительского риска при предоставлении автомобилей в аренду, основанную на предсказании вероятности ДТП?**
2. **Какие другие факторы следует учесть в модели, чтобы повысить точность прогнозов и понимание рисков?**
3. **Требуется ли оборудование автомобилей дополнительными датчиками или камерами для обеспечения дополнительной безопасности?**

Для успешной реализации проекта мне предоставлен доступ к базе данных происшествий, и моя задача – сформировать инновационную систему оценки риска ДТП, способствующую повышению безопасности на дорогах.

**Описание данных**:

<p style="font-size: 150%; text-align: center;font-weight: bold;"> ER - диаграмма </p>

![](https://pictures.s3.yandex.net/resources/1.7_2880border_1_1654004672.png)
