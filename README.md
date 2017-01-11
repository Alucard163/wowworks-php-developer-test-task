# Тестовое задание на вакансию php разработчика в компанию wowworks
						
Необходимо сделать конвертер PDF в HTML слайдер. Основной алгоритм заключается в следующем:
						
1. Открываем страницу, которая содержит форму для загрузки PDF.
2. Выбираем PDF файл, нажимаем кнопку «Конвертировать».
3. Появляется «полоса загрузки», которая в процентах показывает процесс конвертации. (реализация этого пункта необязательна, но будет плюсом)
4. После того как процесс завершен, открывается новая страница на которой отображается HTML слайдер. В качестве слайдов используются изображения страниц PDF файла.
5. Также на странице слайдера есть кнопка «Скачать», при нажатии на которую скачивается zip архив, содержащий:						
  * index.html, который содержит слайдер.
  * папку images, в которой хранятся изображения, конвертированные из PDF
  * папку assets, в которой хранятся необходимые ресурсы, например JS- библиотека слайдера.
6. После генерации архива оставлять ссылку для просмотра слайдера и повторного скачивания архива, доступную в течение 30 минут после генерации
7. Так же необходимо реализовать REST api метод для получения списка ссылок изображений конкретного слайдера (по его id) для генерации кастомных слайдеров на сторонних сайтах (json)

### Требования / Ограничения	

##### PDF				
* Ориентация – портретная;
* Количество страниц – не больше 20;
* Размер файла – не более 50 Мб.
						
##### Технологии				
* PHP, HTML, JS;
* Возможно использование готовых классов и библиотек;
* Framework – предпочтительно Yii2 или без framework’ов; 
* Возможно использование exec();
* Комментарии в коде – приветствуются.
						
##### Результат				
* Ссылка на код на Github / BitBucket;
* Как плюс, ссылка на работающий пример. 
