# Проект исследования поведения пользователей в мобильном приложении  

**Задачи**  
- Провести исследование и выяснить сколько всего у нас пользователей, какой путь проходят пользователи приложения и построить продуктовую воронку, посмотреть корректно ли у нас разбиты группы для эксперимента и провести А/А тест.  
- Провести А/В тесты и проверить как изменения шрифта приложения повлияло на пользователей.  

**При проведении исследования в наличие были такие данные:**  

- Название события (переход на страницу);  
- ID пользователя;  
- время события;  
- 3 группы, 2 - контрольных и 1 - экспериментальная. 

**Вывод**   
После проведения тестов у нас возникает разница в долях между в оформлении заказов - справка и офрмление заказов - оплата, но так как было 40 тестов можно считать, что эти тесты дали ложный результат. Но, если детальней изучить воронку, то можно заметить, что у новой группы показатели конверсии, практически везде лучше. Исходя из проведенного анализа, я бы сказал, что шрифты менять в этой ситуации можно и оно даже немного улучшает конверсию.

**Используемые библиотеки**  
pandas, plotly, numpy, stats, cmath, datetime

## Ссылка на просмотр через nbviewer: https://nbviewer.jupyter.org/github/vitaliikhrystevych13/Projects/blob/main/User_Behavior_Research_Project/User_Behavior_Research_Project.ipynb  

