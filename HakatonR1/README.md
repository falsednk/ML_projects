# hakatonR1
Цель этого проекта - разработка модели склонности (бинарной классификации) к покупке клиентом оборудования после коммуникации с ним в одном из каналов.

Датасет собран для случайного множества клиентов ('id' – идентификатор клиента), с которыми была попытка коммуникации в одном из каналов ('channel_name'). Целевая переменная ('target') равна единице, если после коммуникации с клиентом была продажа оборудования и нулю если нет. Поле 'period' соответствует месяцу сбора признаков на клиента. Лаг между датой коммуникации и сборкой признаков на клиента: 2 месяца.
