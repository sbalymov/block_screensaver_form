""Программа""  "имитирует"  действие пользователя для предотвращения блокировки экрана.
Каждый "Timer interval" вызывается функция которая, проверяет была ли активность пользователя за последнюю минуту,
если активности не было то курсор переместится на 1 пиксель к началу координат, при достижении координат близких к нулю, курсор переместится в центр экрана.

Поле "Timer interval" принимает положительные целочисленные значения в минутах, после закрытия окна данные поля "Timer interval" сохраняются.

Для старта, ввести если требуется значения в поле "Time interval" и нажать на кнопку "ON".
При необходимости изменить интервал, остановить клавишей "OFF" , ввести новое значение и нажать кнопку "ON".

.NET Framework 4.7.2