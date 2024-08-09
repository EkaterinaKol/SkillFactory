# Анализ оттока клиентов из банка

## Оглавление  
[1. Описание проекта](README.md#описание-проекта)  
[2. Краткая информация о данных](README.md#краткая-информация-о-данных)  
[3. Результаты](README.md#результаты)      

### Описание проекта    
Банк планирует разработать кампанию лояльности по удержанию клиентов, для этого ему необходимо выяснить основные причины оттока клиентов. Иными словами, нужно установить, чем ушедшие клиенты отличаются от лояльных и как между собой связаны различные признаки, определяющие клиентов.\
В проекте с использованием библиотеки *Plotly* выполнена визуализация данных, помогающая ответить на поставленные банком вопросы.

:arrow_up:[к оглавлению](README.md#оглавление)

### Краткая информация о данных
Имеется датасет, в котором содержатся сведения о 10 000 клиентов банка. Датасет можно скачать [здесь](https://lms-cdn.skillfactory.ru/assets/courseware/v1/c903ecd0b0c995c44213d620ab6ae94d/asset-v1:SkillFactory+DSPR-2.0+14JULY2021+type@asset+block/churn.zip).\
В датасете представлены следующие признаки:

  - *RowNumber* — номер строки таблицы (это лишняя информация, поэтому можете сразу от неё избавиться)
  - *CustomerId* — идентификатор клиента
  - *Surname* — фамилия клиента
  - *CreditScore* — кредитный рейтинг клиента (чем он выше, тем больше клиент брал кредитов и возвращал их)
  - *Geography* — страна клиента (банк международный)
  - *Gender* — пол клиента
  - *Age* — возраст клиента
  - *Tenure* — сколько лет клиент пользуется услугами банка
  - *Balance* — баланс на счетах клиента в банке
  - *NumOfProducts — количество услуг банка, которые приобрёл клиент
  - *HasCrCard* — есть ли у клиента кредитная карта (1 — да, 0 — нет)
  - *IsActiveMember* — есть ли у клиента статус активного клиента банка (1 — да, 0 — нет)
  - *EstimatedSalary — предполагаемая заработная плата клиента
  - *Exited* — статус лояльности (1 — ушедший клиент, 0 — лояльный клиент).

:arrow_up:[к оглавлению](README.md#оглавление)

### Результаты
Построены следующие графики:
 - [Круговая диаграмма](https://htmlpreview.github.io/?https://github.com/EkaterinaKol/SkillFactory/blob/main/bank_%D1%81ustomer_churn/plotly_figures/fig_1.html), отражающая соотношение ушедших и лояльных клиентов;
 - [Гистограмма](https://htmlpreview.github.io/?https://github.com/EkaterinaKol/SkillFactory/blob/main/bank_%D1%81ustomer_churn/plotly_figures/fig_2.html) распределения баланса пользователей, у которых на счету больше 2 500 долларов;
 - [Коробчатая диаграмма](https://htmlpreview.github.io/?https://github.com/EkaterinaKol/SkillFactory/blob/main/bank_%D1%81ustomer_churn/plotly_figures/fig_3.html) распределений баланса ушедших и лояльных клиентов;
 - [Коробчатая диаграмма](https://htmlpreview.github.io/?https://github.com/EkaterinaKol/SkillFactory/blob/main/bank_%D1%81ustomer_churn/plotly_figures/fig_4.html) распределений возраста ушедших и лояльных клиентов;
 - [Точечная диаграмма](https://htmlpreview.github.io/?https://github.com/EkaterinaKol/SkillFactory/blob/main/bank_%D1%81ustomer_churn/plotly_figures/fig_5.html), отражающая зависимость кредитного рейтинга клиента от его предполагаемой зарплаты;
 - [Круговые диаграммы](https://htmlpreview.github.io/?https://github.com/EkaterinaKol/SkillFactory/blob/main/bank_%D1%81ustomer_churn/plotly_figures/fig_6.html), отражающие cоотношения ушедших и лояльных клиентов отдельно для мужчин и женщин;
 - [Cтолбчатая диаграмма](https://htmlpreview.github.io/?https://github.com/EkaterinaKol/SkillFactory/blob/main/bank_%D1%81ustomer_churn/plotly_figures/fig_7.html), демонстрирующая зависимость оттока клиентов от числа приобретенных ими услуг;
 - [Cтолбчатая диаграмма](https://htmlpreview.github.io/?https://github.com/EkaterinaKol/SkillFactory/blob/main/bank_%D1%81ustomer_churn/plotly_figures/fig_8.html), отражающая зависимость оттока клиентов от статуса активного клиента; 
 - [Тепловая картограмма](https://htmlpreview.github.io/?https://github.com/EkaterinaKol/SkillFactory/blob/main/bank_%D1%81ustomer_churn/plotly_figures/fig_9.html), демонстрирующая долю ушедших клиентов по странам;
 - [Тепловая карта](https://htmlpreview.github.io/?https://github.com/EkaterinaKol/SkillFactory/blob/main/bank_%D1%81ustomer_churn/plotly_figures/fig_10.html) зависимости доли ушедших клиентов от кредитного рейтинга и количества лет с банком.\
 По всем визуализациям сделаны заключения. Сделаны выводы о том, чем ушедшие клиенты отличаются от лояльных и как между собой связаны различные признаки, определяющие клиентов.

:arrow_up:[к оглавлению](README.md#оглавление)



