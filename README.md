**Проект состоит из двух основных разделов:**  
- `app` - папка с исходниками, Вы работаете именно в ней.  
- `build` - туда попадает скомпилированные файлы HTML и CSS (то, что вы видите в браузере).  

---
Внутри папки `app` есть два раздела, `html` и `style`. Рассмотрим их.  
> `html` - содержит папку `views` и html файлы (страницы).  
`views` - содержит набор повторяющихся html-блоков, которые могут использоваться на разных страницах.  
>
> `style` - содержит папку `sass` и главный файл импорта стилей `main.scss`, внём происходит подключение всех scss-файлов проекта.  
В папке `sass`, мы создаем scss файлы, и подключаем их в main.scss, как это сделано для файла `example.scss`  

> Настройки виртуального сервера позволяют работать одновременно с разными файлами, для это необходимо перезапустить сборку, и выбрать только что созданный файл из списка файлов.  


**1. Установка пакетов:**
> npm i

**2. Запуск сборщика:**
> gulp watch

---
**Содержимое**
- сборка умеет собирать и минифицировать SCSS, также есть автопрефиксер.
- поддерживает шаблоны html, позволяя собирать их из разных частей.
- работа с исходниками происходит в папке app.

---
**Внимание! Убедитесь, что у вас установлен NodeJS(рекомендованная версия)**  
**https://nodejs.org/ru/download/**

**Скачать редактор как у меня можно тут:**  
**https://code.visualstudio.com/**


---
Подписывайся:
- **telegram:** **[@html_mentor](https://t.me/html_mentor)**
- **instagram:** **[@html.mentor](https://www.instagram.com/html.mentor)**
