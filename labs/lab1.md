# Лабораторная 1

Создание модели из примитивов - Моделирование транспорта

## Требования

* Использовать только примитивы и трансформацию примитивов
* **НЕЛЬЗЯ** использовать Edit Mode
* Все работы должны быть разными (нельзя сделать одну и ту же модель/тип самолета или автомобиля)
* Всем примитивам неободимо назначить цвет объекта (Properties / Viewport Display / Color)
* В работе должно быть **НЕ МЕНЕЕ** 9 примитивов (максимальное количество не ограничено)
* Моделируемый объект должен быть реальным (например в случае автомобиля - реальная марка и модель, а не просто "машина")
* Дать название примитивав (например "правое колесо", "дверь", "лобовое стекло")
* Назначить всем примитивам родителей, т.е. составить правильную иерархию, например, колесо должно иметь в родителях ось, ось может быть частью кузова и т.д.

## Варианты

1. Автомобиль
2. Морской транспорт
3. Воздушный транспорт
4. Самокат / Велосипед / Моноколесо / и т.п.

Подварианты:

| №   | Автомобили                     | Морской транспорт                       | Воздушный транспорт                               | Самокаты, велосипеды, моноколесо |
| --- | ------------------------------ | --------------------------------------- | ------------------------------------------------- | -------------------------------- |
| 1   | Грузовой автомобиль с прицепом | Контейнеровоз                           | Низкоплан с двумя турбовентиляторными двигателями | Самокат                          |
| 2   | Седан                          | Яхта                                    | Биплан с поршневым двигателем                     | Велосипед                        |
| 3   | Самосвал                       | Рыболовное судно                        | Летающее крыло                                    | Моноколесо                       |
| 4   | Кроссовер                      | Нефтеналивное судно (танкер)            | Самолет-амфибия с поплавками                      | Гироскутер                       |
| 5   | Минивэн                        | Круизный лайнер                         | Одновинтовой вертолет с рулевым винтом            | Сигвей                           |
| 6   | Грузовик                       | Паром                                   | Вертолет с двумя продольными винтами              | Трицикл                          |
| 7   | Спортивный автомобиль          | Рыболовный траулер                      | Вертолет с соосной схемой                         | Гироскутер                       |
| 8   | Универсал                      | Пожарное судно                          | Легкий планер без мотора                          | Мотороллер                       |
| 9   | Кабриолет                      | Судно на подводных крыльях              | Дельтаплан                                        | Электроплатформа                 |
| 10  | Пикап                          | Спасательный катер на воздушной подушке | Шестимоторный турбовентиляторный высокоплан       | Трициклопод                      |

Подвариант можно выбрать самостоятельно. Ограничиваться списком выше не обязательно.

**НУЖНО**: Найти определенную модель и производителя, сохранить схемы и фотографии.

## Пример - Воздушный транспорт / Дельталет

Из таблицы подвариантов находим понравившийся нам "Дельтаплан". Вместо планера без двигателя, будем делать его с силовой установкой, т.е. Дельталет.

Находим в поисковике схемы для строительства своего дельталета.

![Схемы дельталета](examples/deltalet_scheme.png)

Схемы нам нужны чтобы примерно представлять устройство того, что мы планируем моделировать. Задачи сделать 100% копию не стоит. Моделируем с помощью приметивов. Крыло создаем из цилиндра, в параметрах которого указываем 3 грани.

![Полученная модель](examples/lab1_demo_full.png)

Итоговая модель должна быть узнаваемой и напоминать то, что мы моделировали.

![4 вида](examples/lab1_demo.png)

Всем примитивам даем названия и назначаем родителей, пытаясь соблюсти логику конструкции (это не обязательное требование, но желательное). Например родитель у колес - стойка шасси и т.п.

![Outliner](examples/lab1_demo_outliner.png)

Для отображения только объектов без содержимого (мешей) в Outliner - нужно убрать галочку "Object Contents" в фильтрах Outliner'а.
