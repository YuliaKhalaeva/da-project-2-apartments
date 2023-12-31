# Исследование объявлений о продаже квартир

В вашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

# Технологии:

* Jupyter Notebook
* Python
  
# Библиотеки:
* Pandas
* Pyplot
* Seaborn

## План работы

### Цель исследования

Познакомиться с рынком недвижимости и узнать какие факторы влияют на конечную стоимость объектов. Полученная информация в ходе исследования будет полезной для создания автоматизированной системы, которая поможет выявлять закономерности, аномалии и мошенические действия.

### Особенности данных

Данные были предоставлены сервисом Яндекс.Недвижимость в виде архива объявлений, которые можно разделить на два типа:

1. пользовательские (выбранные пользователем вручную)

2. автоматические (полученные на основе картографических данных)

### План работы и задачи

В соответствии с поставленной целью и имеющимися данными, был определен следующий план работы:

I Произвести предоработку данных:

- выявить пропуски, аномалии, дубликаты;
- выбрать способ устранения таких данных(заменить, удалить и т.д.);
- привести данные к одному типу;

II Добавить в данные следующие столбцы:

- цена одного квадратного метра;
- день недели публикации объявления (0 — понедельник, 1 — вторник и так далее);
- месяц публикации объявления;
- год публикации объявления;
- тип этажа квартиры (значения — «первый», «последний», «другой»);
- расстояние до центра города в километрах (переведите из м в км и округлите до целых значений).

III Провести исследовательский анализ данных:

- Изучить параметры объектов;
- Построить отдельные гистограммы для каждого из них;
- Изучить, как быстро продавались квартиры;
- Оценить какие факторы больше всего влияют на общую (полную) стоимость объекта;
- Посчитать среднюю цену одного квадратного метра в 10 населённых пунктах с наибольшим числом объявлений. Выделить населённые пункты       с самой высокой и низкой стоимостью квадратного метра. 

IV Сделать выводы на основе проведенных исследований.
