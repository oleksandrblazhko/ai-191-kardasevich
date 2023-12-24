### Аналіз функціональних та нефункціональних вимог
|<p style="text-align: center;">Вимоги<br>(FR, NFR)|<p style="text-align: center;">Загроза<br>порушення<br>конфіденційності|<p style="text-align: center;">Загроза<br>порушення<br>цілісності|<p style="text-align: center;">Загроза<br>порушення<br>доступності|
|---|---|---|---|
|FR 1.1 Реєстрація клієнта здійснюється через панель сайту призначену дляклієнтів.|<p style="text-align: center;">-|<p style="text-align: center;">+|<p style="text-align: center;">+|
|FR 1.2 Потрібен валідний email, номер телефону та обрані користувачем ім`я і пароль.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 1.3 Користувач не може ввести пароль менше 6 символів.|<p style="text-align: center;">-|<p style="text-align: center;">+|<p style="text-align: center;">+|
|FR 1.5 Всі поля не повинні бути порожніми.|<p style="text-align: center;">-|<p style="text-align: center;">+|<p style="text-align: center;">+|
|FR 1.6 При успішної аутентифікації система повинна оповістити користувача.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 2.1 Зареєструвати працівника (ролі: Працівник, Керуючий, Адміністратор) може тільки авторизований користувач з роллю Менеджер, або Адміністратор.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 2.2 Реєстрація працівника здійснюється через панель управління персоналом.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 2.3 Потрібні: Дійсний e-mail, номер телефону, ПІБ працівника, дата народження, посада.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 2.4 Працівник повинен мати унікальний е-mail в системі.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 2.5 Всі поля не повинні бути порожніми.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 2.6 При успішній реєстрації на e-mail працівника буде відправлено повідомлення з підтвердженням реєстрації і його паролем.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 3.1 Потрібен вже зареєстрований користувач.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 3.2 Аутентифікація Клієнта здійснюється через панель сайту призначену для клієнтів.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 3.3 Клієнт повинен ввести правильне ім`я користувача.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 3.4 Клієнт повинен ввести вірний пароль.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 4.1 Потрібен вже зареєстрований Працівник.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 4.2 Авторизація Працівника здійснюється через панель сайту призначену для працівників.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 4.3 Працівника повинен ввести правильне ім&#39;я користувача.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 4.4 Працівника повинен ввести вірний пароль.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 5.1 Клієнт повинен вибрати розділ сайту «Пошук доступних номерів».|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 5.2 Клієнт повинен ввести потрібні йому дати прибуття і відбуття.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 5.3 Клієнт може, за бажанням, ввести параметри цікавить його номера.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 5.4 Клієнту будуть виведені доступні номери відповідні його побажанням.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 6.1 Клієнт вибирає номер зі списку отриманого в результаті пошуку «FR 1».|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 6.2 Якщо клієнт не авторизований він повинен увійти в обліковий запис або зареєструватися ввівши дані у спливаючому вікні.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 6.3 Авторизований клієнт перенаправляється на сторінку з повним описом його бронювання.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 6.4 Клієнт підтверджує бронювання.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 7.1 Працівник заходить в панель управління замовленнями.|<p style="text-align: center;">-|<p style="text-align: center;">+|<p style="text-align: center;">+|
|FR 7.2 Вибирає опцію «Створити бронювання».|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 7.3 Працівник вводить дати заїзду та від&#39;їзду і параметри пошуку.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|FR 7.4 Працівник вибирає номер з отриманого списку.|<p style="text-align: center;">-|<p style="text-align: center;">+|<p style="text-align: center;">+|
|FR 7.5 Працівник закріплює номер за клієнтом.|<p style="text-align: center;">-|<p style="text-align: center;">+|<p style="text-align: center;">+|
|FR 7.6 Працівник підтверджує бронювання.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|NF 1 Система являє собою Android-застосунок.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|NF 2 Застосунок підтримує Android-подібні ОС, з версією Android не нижче 5.0.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
|NF 3 Для бронювання потрібно підключення до Інтернету, для перегляду збережених – ні.|<p style="text-align: center;">-|<p style="text-align: center;">-|<p style="text-align: center;">-|
