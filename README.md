Розробка HTML-структури форми: Створив форму для введення суми кредиту та періоду погашення.

Установка обмежень та інтерфейсу для вводу даних: Для кожного поля встановлено атрибути min, max та step, а також додано повзунки для відображення діапазону значень.

Реалізація перевірки вводу та відображення повідомлень про помилку: Створені обробники подій для вводу даних, які перевіряють валідність введених значень і відображають відповідні повідомлення про помилку.

Розрахунок платежів при правильному введенні даних: Для розрахунку розміру платежів створена функція calculateRepayments, яка виконує розрахунок і виводить результати на сторінку.

Активація кнопки "Отримати кредит" при відповідності усім вимогам валідації: Доданий обробник події для перевірки валідності усіх полів форми. Якщо форма валідна, кнопка стає активною.

Оновлення відображення результатів при внесенні змін: Додані обробники подій для відслідковування змін у полях форми та відображення розрахунків під час введення даних.

Відображення повідомлень про помилку при невалідному вводі: Використані стандартні механізми HTML5 валідації разом із власними повідомленнями про помилки для кожного поля.
