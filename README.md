# Gold Hunt
Тестове завдання: PDP

Password protection: test123
**PDP** [https://stepan-rozhko-store.myshopify.com/products/red-and-green-pencil?variant=51049467773159](https://stepan-rozhko-store.myshopify.com/products/red-and-green-pencil?variant=51049467773159)


## 📦 Технології
- Shopify (Liquid)
- SCSS --> css
- JavaScript


## 📁 Структура
``` bash 
assets/main.css 
scss/main.scss
sections/main-product.liquid
snippets/swatch-input.liquid
snippets/swatch.liquid
snippets/buy-buttons.liquid
```

## 🛍️ Нотатки розробнику
1. Компіляція. Додати новий файлик у папку SRC/SCSS, додати імпорт у main.scss. Для копіляції - gulp styles , gulp watch. 
2. Для галереї підключено Swiper. Додано можливість зміни:
а) Кількість слайдів, що відображаються одночасно
б) Увімкнення/вимкнення пагінації
в) Увімкнення/вимкнення стрілок навігації
г) Відступ між слайдами
3. Фільтрація фото за кольором реалізована додаванням відповідного слова у ALT зображення - Red, Green + JS.
4. Акордеон. Заголовк та вміст складаються з різних метаполів. Після чого в коді вони додаються у відповідні масиви, і за допомогою FOR відбувається їхній рендер. Це зроблено так, через те що тут один продукт, в іншому випадку можна було б налаштувати метаобєкти.
