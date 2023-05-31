# AB_test

**Название проекта**: Принятие решений в бизнесе на основе анализа А/В тестирования.   
    
**Описание проекта**: Необходимо приоритизировать гипотезы подготовленные вместе с отделом маркетинга и запустить А/В тест с дальнейшим анализом результатов.
    
**Цель проекта**: Приоритизация гипотез и оценка результатов А/В теста.
    
Описание данных:
    
1.Данные для первой части - файл /datasets/hypothesis.csv:
- Hypothesis — краткое описание гипотезы;
- Reach — охват пользователей по 10-балльной шкале;
- Impact — влияние на пользователей по 10-балльной шкале;
- Confidence — уверенность в гипотезе по 10-балльной шкале;
- Efforts — затраты ресурсов на проверку гипотезы по 10-балльной шкале. Чем больше значение Efforts, тем дороже проверка гипотезы.   

2.Данные для второй части - файл /datasets/orders.csv
- transactionId — идентификатор заказа;
- visitorId — идентификатор пользователя, совершившего заказ;
- date — дата, когда был совершён заказ;
- revenue — выручка заказа;
- group — группа A/B-теста, в которую попал заказ.
    
Файл /datasets/visitors.csv:
- date — дата;
- group — группа A/B-теста;
- visitors — количество пользователей в указанную дату в указанной группе A/B-теста
