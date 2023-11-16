<h2>TestPlan</h2>
<p>План автоматизации тестирования возможности записаться на обучение профессии «Тестировщик ПО» на веб-сайте <a href="https://netology.ru/">Нетологии</a>.</p>

<h2>Сценарии для автоматизации.</h2>

<p>Проверяем зарегистрированных и незарегистрированных пользователей.</p>

<h3>Сценарии навигации до формы записи на курс:</h3>

<h4>1.1 Вариант входа через "Каталог курсов" + нажатие кнопки "Найти курс":</h4>
<ol>
  <li>Перейти на сайт <a href="https://netology.ru">Нетологии</a>.</li>
  <li>Кликнуть на вкладку "Каталог курсов" в верхней части страницы.</li>
  <li>В открывшемся поле поиска ввести "Тестировщик ПО" и кликнуть по кнопке "Hайти курс".</li>
  <li>В открывшемся окне с результатами поиска выбрать - "Тестировщик ПО".</li>
</ol>
<h5>• Ожидаемый результат: Открывается страница с информацией по программе обучения Тестировщик ПО, на которой есть форма записи на курс.</h5>

<h4>1.2 Вариант входа через "Каталог курсов" + нажатие иконки "Тестировщик ПО" в появившемся окне:</h4>
<ol>
  <li>Перейти на сайт <a href="https://netology.ru">Нетологии</a>.</li>
  <li>Кликнуть на вкладку "Каталог курсов" в верхней части страницы.</li>
  <li>В открывшемся поле поиска ввести "Тестировщик ПО".</li>
  <li>В открывшемся окне с результатами выбрать - "Тестировщик ПО".</li>
</ol>
<h5>• Ожидаемый результат: Открывается страница с информацией по программе обучения Тестировщик ПО, на которой есть форма записи на курс.</h5>

<h4>1.3 Вариант входа через "Каталог курсов" + выбор вкладки "Тестировщик ПО" в появившемся окне:</h4>
<ol>
  <li>Перейти на сайт <a href="https://netology.ru">Нетологии</a>.</li>
  <li>Кликнуть на вкладку "Каталог курсов" в верхней части страницы.</li>
  <li>В открывшемся окне найти ячейку "Программирование".</li>
  <li>Открывшееся окно с результатами прокрутить вниз до вкладки - "Тестировщик ПО".</li>
</ol>
<h5>• Ожидаемый результат: Открывается страница с информацией по программе обучения Тестировщик ПО, на которой есть форма записи на курс.</h5>

<h4>1.4 Вариант входа через "Раздел: Направления обучения":</h4>
<ol>
  <li>Перейти на сайт <a href="https://netology.ru">Нетологии</a>.</li>
  <li>Найти на блок "Направления обучения" на странице.</li>
  <li>Hайти ячейку "Программирование" и кликнуть по ней.</li>
  <li>Открывшееся окно с результатами прокрутить вниз до вкладки - "Тестировщик ПО" и кликнуть по ней.</li>
</ol>
<h5>• Ожидаемый результат: Открывается страница с информацией по программе обучения Тестировщик ПО, на которой есть форма записи на курс.</h5>

<h4>1.5 Вариант входа через "Раздел: Скидка до - 65%":</h4>
<ol>
  <li>Перейти на сайт <a href="https://netology.ru">Нетологии</a>.</li>
  <li>Найти в низу страница блок "Скидки до - 65%" и нажать кнопку подробнее .</li>
  <li>В появившимся окне нажать кнопку "выбрать курс"</li>
  <li>Открывшееся окно с результатами прокрутить вниз до вкладки - "Тестировщик ПО" и кликнуть по ней.</li>
</ol>
<h5>• Ожидаемый результат: Открывается страница с информацией по программе обучения Тестировщик ПО, на которой есть форма записи на курс.</h5>

<h2>Сценарии заполнения и отправки формы записи на курс Тестировщик ПО для <span style="text-decoration: underline;">Зарегистрированного пользователя</span></h2>


<h4>Позитивный сценарий заполнения формы</h4>
<ul>
  <li>Заполнить валидными данными поле Имя (ввести любые данные без использования цифр и спец. символов, содержащие ваше в поле <strong> ИМЯ </strong>).</li>
  <li>Заполнить валидными данными поле Номер телефона (в формате +9 (999) 999-99-99).</li>
  <li>Кликнуть кнопку <em>Записаться</em>.</li>
</ul>

<h5>Ожидаемый результат:</h5>
<p> Заявка отправлена, появляется сообщение об успешной отправке заявки.</p>

<h4> Негативный сценарий заполнения формы с использованием пустой формы "Имя" </h4>
<ol>
  <li>Заполнить невалидными данными поле Имя (ввести любые данные без использования кириллицы в поле <strong> ИМЯ </strong>).</li>
  <li>Ввести в поле Номер телефона валидные данные (в формате +9 (999) 999-99-99).</li>
  <li>Попытаться отправить форму, кликнув на кнопку <em>Записаться</em>.</li>
</ol>

<h5>Ожидаемый результат:</h5>
<p>Форма не отправляется, появляется сообщение об ошибке с указанием ошибки "Имя заполнено неверно".</p>

<h4> Негативный сценарий заполнения формы с использованием невалидного номера телефона </h4>
<ol>
  <li>Заполнить валидными данными поле Имя (ввести любые данные без использования цифр и спец. символов, содержащие ваше в поле <strong> ИМЯ </strong>).</li>
  <li>Ввести в поле Номер телефона невалидные данные (например, набор символов, не соответствующий формату +9 (999) 999-99-99).</li>
  <li>Попытаться отправить форму, кликнув на кнопку <em>Записаться</em>.</li>
</ol>

<h5>Ожидаемый результат:</h5>
<p>Форма не отправляется, Поле Номер телефона подсвечивается красным, появляется сообщение об ошибке «Поле Номер телефона заполнено неверно», форма не отправлена.</p>


<h4> Негативный сценарий заполнения формы : Оставление форм пустыми </h4>
<ol>
  <li>Оставить поле <em> Имя </em> </li>
  <li>Оставить поле <em> Телефон </em> пустым .</li>
  <li>Попытаться отправить форму, кликнув на кнопку <em>Записаться</em>.</li>
</ol>

<h5>Ожидаемый результат:</h5>
<p>Форма не отправляется, пустые поля подсвечены красным, появляется сообщение об ошибке вида «Заполните поле».</p>