# Practice_Linq
Проект зі Статистики Футболу
Цей проект на C# аналізує дані футбольних матчів із JSON-файлу (results_2010.json), який містить інформацію про різноманітні футбольні гри. Проект включає запити для фільтрації та відображення конкретної інформації про матчі. Нижче наведено короткий огляд проекту та інструкції щодо його запуску.

Структура Проекту
Program.cs: Основний файл, що містить клас Program з методом Main та всіма методами запитів.
FootballGame.cs: Клас, що представляє футбольний матч із властивостями, такими як дата, команди, рахунок і т. д.
results_2010.json: JSON-файл, що містить дані про футбольні матчі.

Використання
Клонуйте або завантажте проект.
Відкрийте проект у середовищі розробки C# (наприклад, Visual Studio).
Переконайтеся, що встановлений необхідний пакет NuGet Newtonsoft.Json.
Запустіть клас Program.

Запити
Проект включає десять запитів (Query1 до Query10), які фільтрують та відображають конкретну інформацію про футбольні матчі на основі різних критеріїв. Кожний метод запиту документований коротким описом призначеного виводу.
Запит 1
Вивести всі матчі, які відбулися в Україні у 2012 році.
Запит 2
Вивести дружбний матч збірної Італії, який вона провела з 2020 року.
Запит 3
Вивести всі домашні матчі збірної Франції за 2021 рік, де вона зіграла у нічию.
Запит 4
Вивести всі матчі збірної Германії з 2018 року по 2020 рік, в яких вона на виїзді програла.
Запит 5
Вивести всі кваліфікаційні матчі UEFA Euro, які відбулися у Києві чи у Харкові, за умови перемоги української збірної.
Запит 6
Вивести всі матчі останнього чемпіоната світу з футболу (FIFA World Cup), починаючи з чвертьфіналів.
Запит 7
Вивести перший матч у 2023 році, в якому збірна України виграла.
Запит 8
Перетворити всі матчі Євро-2012, які відбулися в Україні, на матчі з визначеними властивостями.
Запит 9
Перетворити всі матчі UEFA Nations League у 2023 році на матчі з визначеними властивостями.
Запит 10
Вивести з 5-го по 10-тий матчі Gold Cup, які відбулися у липні 2023 р.