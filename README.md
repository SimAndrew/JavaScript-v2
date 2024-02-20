## Курс JavaScript v2.0

[Ссылка на курс](https://itgid.info/ru/course/js20)

[Ссылка на сертификат](https://itgid.info/ru/certificate/view?Certificate[uid]=b2r7ayvpur8k)

---

### Пример задания и его решения, фото: Unit 18

![Gif](https://github.com/SimAndrew/Html-Css-for-Javascript/assets/44125451/0abca8b9-23f9-4f14-b7f6-851ae4dd20ca)

![image](https://github.com/SimAndrew/forkify-app-js/assets/44125451/b1e69b1d-dc79-4a20-ae9b-73ea00ece2af)

---

### Пример задания и его решения: Unit 18 Task 1 `unit_18.js`

```
Task 1 ============================================
<p>Дан массив a1 = [4,5,6,7,12,34,56,78,90,11] - с помощью forEach переберите массив и 
создайте новый массив a1_res куда добавьте элементы данного массива умноженные на 2. 
Действия должны запускаться при вызове функции t1.</p>

let a1_res = []

function t1() {
  let a1 = [4, 5, 6, 7, 12, 34, 56, 78, 90, 11];
  a1.forEach(elem => {
  a1_res.push(elem * 2);
});

document.querySelector('.out-1').innerHTML = a1_res;
}

document.querySelector('.b-1').onclick = t1;
```

---

### Технологии:

- Синтаксис javascript
- Работа с формами
- DOM (document object model)
- Операторы ветвления
- Операторы условного выбора
- Циклы (for, while, do while)
- Вложенные циклы
- Функции, аргументы, return
- Массивы
- Методы массивов
- Двумерные массивы
- Объекты
- Set - наборы
- Перебор объектов
- События мыши
- События клавиатуры
- Событие touch
- Try catch
- LocalStorage
- AJAX, XMLHTTPRequest
- Fetch, Promise
- Async функции
- ООП

---

### Уроки:

- Спринт 01. Стартуем и пишем первую программу

  branch: `sprint-01-we-start-and-write-the-first-program`
- Спринт 02. Основы ввода данных
- Спринт 03. Оператор If, else, switch case
- Спринт 04. Работаем с формами: input, range, textarea, checkbox
- Спринт 05. Циклы в JavaScript (часть 1)
- Спринт 06. Вложенные циклы в JavaScript (часть 2)
- Спринт 07. Функции и все о них
- Спринт 08. Цикл While, Do While
- Спринт 09. Работаем с DOM
- Спринт 10. Массивы в JavaScript
- Спринт 11. Добавление и удаление элементов в массиве, pop, push,splice
- Спринт 12. Двумерные массивы
- Спринт 13. Ассоциативный массив
- Спринт 14. Практика по массивам - получаем прогноз погоды по API
- Спринт 15. Set в JavaScript
- Спринт 16. Перебор массивов: for, for in, for of
- Спринт 17. Методы массивов: map, filter ( часть 1)
- Спринт 18. Методы массивов: join, split, forEach ( часть 2)
- Спринт 19. События мыши в JavaScript
- Спринт 20. События клавиатуры в JavaScript
- Спринт 21. Краткий обзор touch событий
- Спринт 22. Обрабатываем ошибки с помощью Try Catch
- Спринт 23. LocalStorage. Сохраняем все
- Спринт 24. Запросы GET, POST. POSTMAN. Работа с API
- Спринт 25. Запросы GET, POST на JS. Асинхронный JS, AJAX
- Спринт 26. Fetch запрос. Async функции, await. AJAX
- Спринт 27. Promise, Цепочки промисов (chaining), PromiseAll
- Спринт 28. ООП в ES6

---

### Структура:

От main идут ветки под каждый спринт.

Branch: `sprint-01-we-start-and-write-the-first-program` ветка с названием урока.

В ней файлы: `unit_01.html, style.css, unit_01.js, images`

Задание в unit_01.js, решение в unit_01.js файле.

---

### Запуск приложения:

- Выбрать ветку например: branch: `sprint-01-we-start-and-write-the-first-program`
- Запустить live server

---

## Course JavaScript v2.0

[Link to the course](https://itgid.info/ru/course/js20)

[Link to certificate](https://itgid.info/ru/certificate/view?Certificate[uid]=b2r7ayvpur8k)

---

### Structure:

From main there is a branch with the name of the lesson. It contains files: html, css, js, images.

Task in js, task solution in js file.

---

### Run the app:

- Select branch
- Run live server