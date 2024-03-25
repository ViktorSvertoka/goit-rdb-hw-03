# Домашнє завдання до Теми 3. Завантаження даних та основи SQL. DQL команди

- Вітаємо! Як настрiй? Сподiваємося, що ви з нетерпiнням очікуєте на новий челендж 😉

- Ласкаво просимо до домашнього завдання, виконавши яке ви зможете вдосконалити свої навички в мові структурованих запитів SQL, зокрема команд DQL (Data Query Language).

- Здатність ефективно створювати та оптимізувати запити DQL є важливою навичкою для обробки та аналізу великих обсягів даних. Ви як майбутні фахівці матимете можливість використовувати ці навички для розв'язання завдань у сфері розробки програмного забезпечення, аналізу даних та багатьох інших галузях.

- У цьому домашньому завданні вам необхідно застосувати свої знання для отримання конкретної інформації із завантаженого раніше (у конспекті до теми 3) датасету, а саме написати кілька SQL команд — запитів до даних.

- Нехай це домашнє завдання розширить вашу перспективу у світі SQL! 🧠

### Підготовка та завантаження домашнього завдання

1. Створіть публічний репозиторій `goit-rdb-hw-03`.
2. Якщо раніше ви не завантажували [цей архів](https://drive.google.com/file/d/1B45tkzH3lIrf2CmQIB2VB0AJRB9Ly7c2/view "Натисни щоб скачати") з даними у форматі `csv`, зробіть це зараз.
3. Виконайте завдання та відправте у свій репозиторій скриншоти запитів і результатів, а також текст SQL коду в текстовому файлі.
4. Завантажте скриншоти і текстовий файл на свій комп’ютер та прикріпіть їх в LMS архівом. Назва архіву повинна бути у форматі ДЗ3_ПІБ.
5. Прикріпіть посилання на репозиторій `goit-rdb-hw-03` та відправте на перевірку.

### Формат здачі

- Прикріплені файли репозиторію архівом із назвою ДЗ3_ПІБ.
- Посилання на репозиторій.

#### 💡 ВАЖЛИВО

- Будь ласка, пронумеровуйте скріншоти, щоб менторам було зрозуміло, до якого етапу ДЗ відноситься кожний з них. Наприклад, якщо файл відноситься до пункту 3, то назва файла має починатися так: p3\_.

## Опис домашнього завдання

1. Напишіть SQL команду, за допомогою якої можна:

вибрати всі стовпчики (За допомогою wildcard “\*”) з таблиці “products”;
вибрати тільки стовпчики name, phone з таблиці shippers,
та перевірте правильність її виконання в MySQL Workbench.

2. Напишіть SQL команду, за допомогою якої можна знайти середнє, максимальне та мінімальне значення стовпчика price таблички products, та перевірте правильність її виконання в MySQL Workbench*.*

3. Напишіть SQL команду, за допомогою якої можна обрати унікальні значення колонок category_id та price. Оберіть порядок виведення на екран за спаданням значення price та виберіть тільки 10 рядків. Перевірте правильність виконання команди в MySQL Workbench.

4. Напишіть SQL команду, за допомогою якої можна знайти кількість продуктів (рядків), які знаходиться в цінових межах від 20 до 100, та перевірте правильність її виконання в MySQL Workbench.

5. Напишіть SQL команду, за допомогою якої можна знайти кількість продуктів (рядків) та середню ціну (price) у кожного постачальника (supplier_id), та перевірте правильність її виконання в MySQL Workbench.

### Критерії прийняття

1. Прикріплені посилання на репозиторій goit-rdb-hw-03 та безпосередньо самі файли репозиторію архівом.

2. Правильно написано всі 6 команд. SQL команди виконуються й повертають необхідні дані.

### Результат виконаного ДЗ

![Results](./assets/01-SQL-requests.png)

![Results](./assets/02-SQL-requests.png)

![Results](./assets/03-SQL-requests.png)

![Results](./assets/04-SQL-requests.png)

![Results](./assets/05-SQL-requests.png)

![Results](./assets/06-SQL-requests.png)

![Results](./assets/all-SQL-requests.png)
