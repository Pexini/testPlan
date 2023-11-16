# TestPlan
План автоматизации тестирования возможности записаться на обучение профессии «Тестировщик ПО» на веб-сайте ["Нетологии"](https://netology.ru/).
=======

 <h2> Сценарии для автоматизации. </h2>

*Проверям зарегистрированных и не зарезистрированых польтзователей.*



<h3> Сценарии навигации до формы записи на курс: </h3>
<h4> 1.1 Вариант входа через "Каталог курсов" + нажатие кнопки  Найти курс: </h4>  
  1. Перейти на сайт <a href="https://netology.ru"> Нетологии </a>. <br> 
  2. Кликнуть на вкладку  <strong> "Каталог курсов" </strong> в верхней части страницы. <br> 
  3. В открывшемся поле поиска ввести Тестировщик ПО и кликнуть по кнопке <strong> Hайти курс </strong>. <br> 
  4. В открывшимся окне с результатами поиска выбрать - <strong> Teстировщик ПО </strong>.  
 <h5> <span class="bold-dot">•</span> Ожидаемый результат: Открывается страница с информацией по программе обечения Тестировщик ПО, на которой есть форма записи на курс. </h5>

<h4> 1.2 Вариант входа через "Каталог курсов" + нажатие иконки "Тестировзик ПО" в появизимся окне:* </h4>
  1. Перейти на сайт <a href="https://netology.ru"> Нетологии </a>. <br>
  2. Кликнуть на вкладку <strong> "Каталог курсов" </strong> в верхней части страницы. <br>
  3. В открывшемся поле поиска ввести <strong>Тестировщик ПО </strong>. <br>
  4. В открывшимся окне с результатами  выбрать - <strong> Тестировщик ПО </strong>. <br>
<h5> <span class="bold-dot">•</span> Ожидаемый результат: Открывается страница с информацией по программе обечения Тестировщик ПО, на которой есть форма записи на курс.</h5>

<h4> 1.3 Вариант входа через "Каталог курсов" + выбор вкладки <strong> Программирование  </strong> : </h4>  
  1. Перейти на сайт <a href="https://netology.ru"> Нетологии </a>. <br> 
  2. Кликнуть на вкладку  <strong> "Каталог курсов" </strong> в верхней части страницы. <br> 
  3. В открывшемся окне найти ячейку <strong> Программирование </strong> и кликнуть по ней. <br> 
  4. Открывшееся окно с результатами прокрутить вниз до вкладки - <strong> Teстировщик ПО </strong> и кликнуть по ней.  
 <h5> <span class="bold-dot">•</span> Ожидаемый результат: Открывается страница с информацией по программе обечения Тестировщик ПО, на которой есть форма записи на курс. </h5>

<h4> 1.4 Вариант входа через <strong> "Раздел : Направления обучения" </strong> </h4>  
  1. Перейти на сайт <a href="https://netology.ru"> Нетологии </a>. <br> 
  2. найти на блок   <strong> "Направления обучения" </strong> <br> 
  3. Hайти ячейку <strong> Программирование </strong> и кликнуть по ней. <br> 
  4. Открывшееся окно с результатами прокрутить вниз до вкладки - <strong> Teстировщик ПО </strong> и кликнуть по ней.  
 <h5> <span class="bold-dot">•</span> Ожидаемый результат: Открывается страница с информацией по программе обечения Тестировщик ПО, на которой есть форма записи на курс. </h5>

<h4> 1.5 Вариант входа через <strong> "Раздел : "Скидка до - 65%" </strong> </h4>  
  1. Перейти на сайт <a href="https://netology.ru"> Нетологии </a>. <br> 
  2. Найти в самом низу страница блок сро скидкой  <strong> "Скидки до - 65%" и нажать кнопку <strong> подробнее </strong>  </strong> <br> 
  3. В появившимся окне нажать кнопку <strong> "выбрать курс"
  4. Открывшееся окно с результатами прокрутить вниз до вкладки - <strong> Teстировщик ПО </strong> и кликнуть по ней.  
 <h5> <span class="bold-dot">•</span> Ожидаемый результат: Открывается страница с информацией по программе обечения Тестировщик ПО, на которой есть форма записи на курс. </h5>

<h2> Сценарии заполнения и отправки формы записи на курс Тестировщик ПО </h2>
<h3> Позитивный сценарий заполнения  формы </h3>
   1.  Заполнить валидными данными поле Имя (под валидными данными понимается имя, набранное кириллицей, длиной от одной буквы, с возможностью использования пробелов и/или тире).
   2.  Заполнить валидными данными поле Номер телефона (под валидным номером телефона понимается номер, состоящий из 11 цифр, начинающийся с префикса +7).
   3.  Заполнить валидными данными поле Электронная почта (под валидной почтой понимается адрес эл.почты, состоящий из 4 частей: локальная часть, символ @, точка и доменное имя ).
   4.  Кликнуть кнопку Записаться.
