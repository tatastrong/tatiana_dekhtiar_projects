# Анализ пользовательского поведения в мобильном приложении

**Описание проекта**

Дизайнеры предлагают поменять шрифты в мобильном приложении для покупки продуктов питания. Чтобы определить целесообразность внесения изменений в дизайн приложения, проведено A/A/B-исследование. Пользователей приложения разбили на 3 группы: 2 контрольные (246 и 247) со старыми шрифтами и одну экспериментальную (248) — с новыми.

**Задачи**: 

 1. Разобраться, как ведут себя пользователи мобильного приложения для покупки продуктов питания.
 2. Выяснить влияет ли шрифт в приложении на поведение пользователей.

**Описание данных**

Доступны данные о действиях пользователей, записанные в логе. Каждая запись в логе — это действие пользователя, или событие, для которого собраны следующие данные:

    EventName — название события;
    DeviceIDHash — уникальный идентификатор пользователя;
	EventTimestamp — время события;
	ExpId — номер эксперимента: 246 и 247 — контрольные группы, а 248 — экспериментальная.

**Навыки**: A/B-тестирование, событийная аналитика, продуктовые метрики, проверка статистических гипотез, визуализация данных

**Инструменты**: Python, Pandas, Matplotlib, Seaborn, Plotly

**Статус проекта**: Завершен
