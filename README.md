# Портфолио: инженер по тестированию

## Обо мне 

Привет! Меня зовут ``Марина``, я начинающий тестировщик. <br>
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
  
``Jira``,``qase.io``,``sitechco``,``Trello``,``Miro``,``Notion``,``Confluence``,``Swagger``,``Swagger``,``Visual Studio Code``,<br>
``Postman``,``Chrome DevTools``,``pgAdmn4``,``SQL``,``SoapUI``,``JMeter``,``Mockoon``,``curl``.

Тестирование веб-ресурсов: создание и ведение тестовой документации (применение техник тест-дизайна, составление тест-планов,  
чек-листов/чит-листов, тест-кейсов, баг-репортов, анализ требований), проведение тестирования и составление отчета по нему.  
Использование различных систем хранения документации (Jira, Confluence, Trello, Qase.io, Sitechko, Checkvist, Miro)  
Работа с базами данных (pgAdmin, практические навыки работы с SQL).  
Тестирование REST API (Postman, curl, DevTools, Mockoon, Swagger),  
тeстирование SOAP сервисов (SOAP UI), нагрузочное тестирование (базовые знания Jmeter).

## Проекты

<p> ✅ Проект 1: Тестирование веб-приложения для учителей от Skyeng</p>
<p>Что нужно было сделать: Изучить представленную документацию и провести тестирование разработаного функционала,  
в том числе REST API тестирование, также проверить состояние основного функционала "Расписание"  
после добавления изменений ("Личные события"). <p>
  
   Для тестирования веб-приложения для учителей Skyeng были составлены и проведены следующие виды тестирования:  
тестирование документации,  
декомпозиция функционала "Личные события" в расписании,  
составление и проведение смоук, регресс, и приемочных тест-кейсов,  
в т.ч. функциональное тестирование по чек-листу,  
также API тестирование (коллекция в Postman).  
Обнаруженые баги задокументированы в Jira.  
Далее проведен анализ метрик и составлен отчет о тестировании.
  
> <a href="https://drive.google.com/file/d/1da3oor3WYHxpcSvdFGXv3wsmRWfvfwNv/view?usp=sharing">Ссылка на проект</a>
  <br> 
  
> <a href="http://joxi.ru/5mdXdYGiJKdXPm" target="_blank"><img src="http://dl3.joxi.net/drive/2023/06/11/0040/0046/2662446/46/61803f89ed.jpg"></a>
  
  В данном проекте были использованы такие инструменты qase.io, Sitechco, Confluence, Jira, Miro, Postman.
  
   
<p>Итоги: В процессе выполнения проекта проведен практически полный цикл тестирования нового функционала,<br>
далее на основе всего рассмотренного - собраны метрики тестирования, по ним хорошо видно, что все в порядке,<br>
добавленный функционал работает в соответствии с требованиями и здравым смыслом, и готов к использованию. <br>
Также сделаны предположения, что и как можно поменять в этом продукте, чтобы улучшить его для клиентов.<p>
 
<p> ✅ Проект 2: тестовое задание. Финал первого курса.
  
<p> Задание 1.
Продукт: консольное приложение (приложение в вакууме) Приложение на вход принимает 3 целых числа, интерпретируемые  
как длины сторон треугольника, а на выходе выводит на экран является ли введенный треугольник равнобедренным или  
равносторонним. Необходимо предложить конкретные значения тестовых данных для тестирования такого приложения.<br>
``При решении`` предложены варианты функционального и нефункционального тестирования, позитивные и негативные сценарии;<br>
используется техника классов эквивалентности.<p> 
<p> Задание 2.
Протестировать лифт в девятиэтажном доме.
'Решение': в виде чеклиста перечислены функциональные и нефункциональные проверки, позитивные и негативные сценарии; <br>
также используется техника классов эквивалентности и граничных значений.<br>
Рассмотрены проверки юзабилити, безопасности, нагрузочное, стрессовое.
<p> Задание 3
Автомат принимает накопительные скидочные карты и при своем расчете учитывает количество баллов, по которому начисляет процент скидки:
От 0 до 100 баллов — 1%; От 100 до 200 баллов — 3%; От 200 до 500 баллов — 5%; От 500 баллов — 10%.
Необходимо составить набор тестовых данных для получения верной скидки.
Составлены таблица классов эквивалентности, граничных значений и продуман набор тестовых данных для автомата. Есть вопросы к спецификации (поведение на гранце значений)<p> 
В проекте 2 использованы таблицы GoogleSheets.

> <a href="https://docs.google.com/spreadsheets/d/1jfKwhkquWbE7_dQqD8cMBaIP__iH8oorEdi0fFqd4OU/edit?usp=sharing">Ссылка на проект</a>
 
<p> ✅ Проект 3: Тестирование API ручки регистрации <p>
<p> Есть запрос регистрации вида:
Request: api/v1/register { login: String, email: String; password: String; confirmPassword: String; }
Response: { code: int; result: String; } <p>
<p> Также есть ручка getUser, которая возвращает информацию о том, существует ли такой пользователь или нет. 
Request: api/v1/getUser { login: String }
Response: { code: int; result: String; }
Все данные сохраняются в базу данных.<p>
<p>При решении составлена таблица тестовых данных и написаны позитивные и негативные API тест-кейсы для проверки ручки регистрации и проверки наличия пользователя. Использовался метод POST.<p>
  
> <a href="https://docs.google.com/document/d/1ferj8KTPhcAywfzWGJXslt9pD3iZE9ZJlgDljWiMJ8w/edit?usp=sharing">Ссылка на проект</a>

  <p> ✅ Проект 4: тестовое задание.<p>
Задание 1: ТЗ от заказчика: "Реализовать форму, которая по введенным данным определяет, является ли человек совершеннолетним.
Приложение должно быть с архитектурой клиент-сервер". Предположим, что разработчик реализовал данную форму (Прилагаются макеты).<br>
Необходимо ответить на вопросы:
- Какие могут возникнуть вопросы к требованиям?<br>
- Какие виды и типы тестирования стоит проводить? Объясните, почему.<br>
- Что больше подойдет для организации тестовой документации по задаче - тест-кейсы или чек-листы? Почему?<br>
- Какие техники тест-дизайна Вы бы использовали? Почему?<br>
- Какие можно выделить негативные и позитивные входные данные?<br>
- Какие теоретически могут быть баги? Опишите 4-6 возможных бага.<br>
- Есть ли баги любого типа на приведенных скриншотах? Если есть, опишите все.<p>
    
> <a href="https://docs.google.com/document/d/16yw7E1QuKPFj3NTT_GyH4yrXfqb6nIrGWOs5_CSo8Is/edit?usp=sharing">Ссылка на проект</a>
  
Задание 2:  cоставить чек-лист проверок для главной страницы сайта cloud.ru
  
> <a href="https://docs.google.com/spreadsheets/d/1M_fw-HeNYLmGkihhJoWfmoGNMH3cudWRVKPFY648KEg/edit?usp=sharing">Ссылка на чек-лист</a> <br>     
 
Задание 3: Тестирование API Яндекс.Погоды. Необходимо с помощью Postman протестировать работу метода со следующими параметрами:<br>
тариф Тестовый / lon 50 lat / 55 / язык русский<br>
Также создать несколько негативных сценариев и убедиться, что при неправильных данных запрос возвращает соответствующий результат <p>
Была создана Postman-коллекция из 4 запросами с методом GET, и 2 переменными: 1 запрос с позитивными данными и 3 запроса с негативными (Тест на превышение лимита запросов для этого тарифа не проводился.)<p>
  > <a href="https://drive.google.com/file/d/1kv3qEtua_dqWu0SFT4M9QMgyaMM3J61w/view?usp=sharing">Ссылка на json</a>
  
Задание 4:  Запросы SQL для данных из 2-х таблиц animal_info и animal_classes.
В процессе выполнения созданы и заполнины таблицы в PGAdmin4, затем там же составлены варианты запросов.<br>

> <a href="https://drive.google.com/file/d/1w4qQWcwHZTCtdm6wNjfEmoVyM1Djl9l-/view?usp=sharing">Ссылка на запросы</a> <br>  
  
<p> ✅ Учебный проект 5.  Составление SQL-запросов - фрагмент с использованием фукции RANK OWER.

<a href="http://joxi.ru/V2VzDLGUGaEnR2" target="_blank"><img src="http://dl3.joxi.net/drive/2023/06/06/0040/0046/2662446/46/b22964d9e3.jpg"></a>
  
 <p>Немного обо мне: есть среднее специальное образование ("Менеджмент и маркетинг") <br>
 и высшее - "Минералогия и Геохимия" МГРИ-МГГРУ, при этом я работала в основном курьером и няней, <br>
 сейчас учусь на QA-инженера и продаю этнические муз инструменты - бубны, диджериду),<br>
 мне так не хватало нагрузки для мозга)) И вообще - нравится изучать новое в этом профиле, <br>
 жду с нетерпением свой первый рабочий проект.<p>
 <br>
    
## Контактная информация
- Email: marinkatik1@gmail.com
