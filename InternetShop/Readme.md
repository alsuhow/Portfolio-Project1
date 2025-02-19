Заказчиком был предоставлен датафрейм с данными продаж интернет-магазина за период

Выполненная работа [ipynb](https://github.com/alsuhow/Portfolio/blob/main/InternetShop/Internet-shop_RFM-analysis.ipynb)   [HTML](https://github.com/alsuhow/Portfolio/blob/main/InternetShop/Internet-shop_RFM-analysis.html)

**Цель работы**: сегментирование покупателей интернет-магазина на основе истории их покупок
_________________________ 
 **NB !Выводы и рекомендации были вынесены в начала файла, сразу после цели задач работы!**

**Примерный вид рекомендаций:**

 **RFM - сегмент_1**
 
**Поведение**: *последняя покупка была _______, так же ___________ средний чек и кол-во покупок _____________*

**Характеристики:**

_____ клиентов, ____% от клиентской базы 
- давность покупок - ___________дня;
- частота покупки - _____ раз;
- сумма покупки - _____;
- глубина покупки (количество позиций в чеке) - _____
- средний чек покупки - _______;
- средняя сумма покупки в месяц - 156 764,00;
- средняя сумма покупки за сезон - 241 256,00
- наибольшие продажи в зимний сезон, наименьшие - в весенний

**Статистические тесты**
- по среднему чеку статистически НЕ отличаются от сегмента ______

**Товарные категории, сезонность:**

- ТОР-3 месяцев с наибольшими суммами продаж _____
- ТОР-3 с наименьшими суммами продаж _____
- ТОР-3 по сумме продаж:____;

**Как работать**

Самая пародоксальная группа! Она составляет 1/3 от существующей клиентской базы, но при этом последние покупки совершались до ____ - более 9 месяцев назад. При этом покупатели этого сегмента имели неплохие количественные показатели, чуть ниже средних по интернет-магазину.

**Основные зоны роста:**

1. Вернуть клиентов! в ручном режиме проверить актуальность базы. Удалить несуществующих, мертвых клиентов (касается в первую очередь юридических лиц! не физиков!). Эти клиенты так давно покупали в интернет-магазине, что уже забыли все наши преимущества и предложения.
2. После актуализации базы подготовить общие акционные предложения и скидки с наиболее привлекательными товарами. В целом в наступающем весеннем периоде отлично покупаются товары групп "_____________". Так же стоит обратить внимание на товары категорий "_________________" - т.к. они так же присутсвовали в ранее оплаченных чеках.
3. Для реанимации клиентов - дать ограниченную по времени крупную скидку на следующую первую покупку. Приурочить её к одному из ближайших праздников - 14 февраля, 23 февраля, 8 марта.


_____________________ 

**Задачи работы**:
1. Сегментирование товарных позиций
2. Проведение исследовательского анализа предоставленных данных:
    - корректность предоставленной в датафрейме информации;
    - поиск явных и неявных дубликатов;
    - работа с типом предоставленной информации;
    - аргументированный ввод / добавление информации, необходиомй для дальнейшего анализа.
3. Предварительный анализ данных:
    - общая информация;
    - кол-во выполненных заказов за период;
    - количество позиций в чеке;
    - средний чек;
    - динамика продаж;
    - анализ явных выбросов, влияющих на проведение анализа
4. Анализ продаж по категориям
    - распределение количества позиций внутри категорий;
    - анализ общей суммы покупок внутри категорий;
    - анализ количества проданных товаров внутри категорий;
    - средний чек внутри категорий;
    - сезонность продаж
5. Сегментирование покупателей на основе истории их покупок
    - RFM анализ
        - обоснование разделения на категории в сегментах recency / frequency / monetary
        - формирование RFM - таблицы
        - анализ полученных данных
        - работа с сегментами:
            - определение наиболее перспективных сегментов для увеличения продаж;
            - рекомендация по формам работы для сегментов
6. Гипотезы
    - есть ли различие величины среднего чека между сегментами
    - есть ли различие в среднем объемсе продаж между сегментами
7. Общие выводы и рекомендации, исходя из полученного анализа
_____________________________________ 
