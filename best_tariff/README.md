## Определение перспективного тарифа для телеком компании  
  
Перед нами данные оператора сотовой связи:
  - о звонках (дата, длительность, идентификатор пользователя, идентификатор звонка),
  - о сообщениях (дата, идентификатор пользователя, идентификатор сообщения),
  - о потраченных мегабайтах интернет трафика (количество МБ, дата, идентификатор пользователя, идентификатор записи),
  - информация о тарифных ставках (название тарифа, стоимость пакета услуг, сколько МБ, смс и звонков входит в пакет услуг и стоимость услуг в случае превышения лимита)
  - информация о пользователях (идентификатор, имя, фамилия, возраст, город, дата регистрации, дата расторжения договора, тариф)  
    
Оператор сотовой связи предлагает своим клиентам два тарифных плана.  
**Цель исследования** - выяснить, какой тариф приносит больше денег, чтобы скорректировать рекламный бюджет.  

Нам предстоит сделать предварительный анализ тарифов на небольшой выборке клиентов. В нашем распоряжении данные 500 пользователей сотовой связи: кто они, откуда, каким тарифом пользуются, сколько звонков и сообщений каждый отправил за рассматриваемый период.  
  
Также мы проверим гипотезы о различиях средней выручки пользователей разных тарифов и о различиях средней выручки пользователей из Москвы и пользователей из других регионов.  
  
Мы проанализируем поведение клиентов и сделаем вывод — какой тариф лучше.
  
**Используемые библиотеки:**    
***pandas***, ***numpy***, ***matplotlib***, ***seaborn***, ***scipy***.
