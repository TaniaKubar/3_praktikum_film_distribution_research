# Исследование рынка российского кинопроката
Заказчик этого исследования — Министерство культуры Российской Федерации. Требуется изучить рынок российского кинопроката и выявить текущие тренды. А также отдельно рассмотреть фильмы, которые получили государственную поддержку, и ответить на вопрос, насколько такие фильмы интересны зрителю. Данные опубликованны на портале открытых данных Министерства культуры. Набор данных содержит информацию о прокатных удостоверениях, сборах и государственной поддержке фильмов, а также информацию с сайта КиноПоиск.

Цель исследования — выявить текущие тренды рынка российского кинопроката, оценить популярность и окупаемость фильмов, получивших государственную поддержку.

Этапы исследования:
- обзор данных
- слияние датасетов
- предобработка данных
- добавление данных
- анализ данных
- общие выводы

## Общие выводы
Все фильмы:

- В выборке много пропусков в колонке с суммой кассовых сборов за период с 2010 по 2014 год. Данные в разрезе года выхода фильма в прокат за период с 2010 по 2014 год не репрезентативны.

- Самая высокая сумма кассовых сборов была в 2018 году и составила 49,6 млрд. руб.

- Самые высокие средняя и медианная суммы сборов были в 2017 году и составили 136 млн. руб. и 9,9 млн. руб. Средние и медианные значения сильно различаются между собой, среднее гораздо больше медианы, это говорит о том, что небольшая часть кассовых фильмов оказывает влияние на среднее значение.

- Больше всего в прокате собирали фильмы "16+", пик сборов отмечается в 2017 году. При этом в 2017 году выходило меньшее количество фильмов в указанной категории, по сравнению с остальными годами, а медианная сумма сборов за один фильм не показала значительного роста, следовательно высокие сборы в 2017 году объясняются небольшим количеством популярных фильмов, обеспечивших внушительную часть сборов.

- Меньше всего по количеству выходивших в год фильмов составила категория "0+". Самые высокие медианные сборы наблюдаются в 2017 году у категорий "6+" и "0+". Можно сделать вывод, что фильмы с указанным возврастным ограничением самые популярные.

- В 2017 году наблюдается значительное уменьшение количества вышедших в прокат фильмов по всем возрастным категориям, кроме категории "18+", по ней спад незначительный.

Фильмы, получившие государственную поддержку:

- Самая сильная корреляция между бюджетом фильма и размером государственной поддержки (возвратной и невозвратной). Коэффициенты корреляции Пирсона составляет 0.64 и 0.59 соответственно. Также наблюдается корреляция кассовых сборов с размером государственной поддержки (возвратной и невозвратной) и бюджетом фильма. Коэффициенты корреляции Пирсона составляют 0.31, 0.46 и 0.36 соотвественно. Корреляция с рейтингом при этом практически отсутствует.

- Среди фильмов, получивших государственную поддержку больше всего было в жанре "драма" - 93, "комедия" - 74 и "мультфильм" - 31. В среднем самую большую поддержку получали фильмы, снятые в жанре "история", "спорт" и "фантастика". При этом полную окупаемость показывают только фильмы, снятые в жанре "спорт". самыми провальными оказались фильмы в жанре "мелодрама", "детский", "драма", "триллер" и "детектив", чаще всего они окупались менее, чем на 10%.

- Больше всего финансирования суммарно получили фильмы в жанре "драма" 5,3 млрд. руб. или 27% всей поддержки, при этом они оказались одними из самых провальных по окупаемости. Самыми провальными также оказались фильмы в жанре "мелодрама", "детский", "триллер" и "детектив", чаще всего они окупались менее, чем на 10%.

- Между рейтингом и жанром не наблюдается какой-либо взаимосвязи. Можно отметить, что самый высокий медианный рейтинг у фильмов в жанре "криминал" - 7.5, а самый низкий в жанре "ужасы" - 5.2.

- Средние и медианные кассовые сборы фильмов, получивших государственную поддержку, составляют 132,4 млн. руб. и 15,72 млн. руб. соответственно и превышают сборы остальных фильмов в целом (70,8 млн. руб. и 2 млн. руб.), и, в частности, произведенных в России и СССР (17 млн. руб. и 0,05 млн. руб.). Наличие государственной поддержки не оказывает никакого влияния на рейтинг фильма.

- Фильмы, финансируемые Фондом кино окупаются гораздо лучше (медианная окупаемость 75,8%), чем финансируемые Министреством культуры (2,9%). Их совместные проекты также практически не окупаются.
