# goit-markup-hw-03

Репозиторій для домашнього завдання #3

Критерії приймання роботи наставником Проект «A1» У корені проекту є папка images з зображеннями.

<!-- «A2» У корені проекту є папка css з файлами стилів. -->
<!-- «A3» Всі стилі написані в одному файлі styles.css, який знаходиться в папці css. -->
<!-- «A4» У назвах файлів відсутні великі літери, пробіли і трансліт, тільки літери і слова англійської
мови. -->
<!-- «A5» Вихідний код відформатований за допомогою Prettier. -->
<!-- «A6» Всі зображення та текстовий контент взяті з макета. -->
<!-- «A7» На всіх HTML-сторінках підключений нормалізатор стилів modern-normalize. -->
<!-- «A7» Код написаний з дотриманням настанови. -->

<!-- Оформлення «B1» Допускається глобальне скидання стилів за селектором тегу для елементів <h1>...<h6>, <p> і <ul>.  -->

«B2» В елементів відсутні зовнішні відступи (властивість margin), що «пробивають» батьківський
елемент.

«B3» В однорядкових колекціях елементів очищений крайній лівий або правий margin елементів (якщо він
є).

«B4» Для відступів між двома сусідніми елементами використовується властивість margin.

«B5» Для проміжку між межею батька і його дитиною використовується властивість padding.

«B6» Розміри зовнішніх відступів (властивість margin) і внутрішніх полів (властивість padding)
елементів задані точно за макетом.

<!-- «B7» Створений загальний допоміжний клас .container для центрування і обмеження
контенту по ширині.  -->

<!-- «B8» Ширина «контейнера» відповідає макету і дорівнює 1200px.  -->

<!-- «B9» «Контейнер»
обгортає контент хедера, футера і секцій. Тобто знаходиться всередині них.  -->

«B10» Для розташування елементів використовується Flexbox, але тільки там, де це необхідно.
Наприклад у шапці, навігації, списках в секціях тощо, тобто там, де розташувати елементи
горизонтально по-іншому неможливо.

«B11» Фінальні розміри блоків в браузері відповідають макету.

«B12» В елементів відсутня фіксована висота, вона визначається їх контентом.

<!-- «B13» У хедера є нижня рамка, необхідно сильно наблизити макет, щоб
побачити її.  -->

«B14» Секції розташовані одна під одною як стопка книг, без зовнішніх відступів.

«B15» Для всіх секцій використовується один клас .section, задані верхні і нижні падінги по 94px, що
відсувають контент всередину секції.

«B16» Для побудови сіток використовується техніка, що описана у конспекті і відео-майстерні.

«B17» У картках на сторінці Портфоліо є рамка (властивість border), але тільки у нижній частині
картки.

<!-- Ну що ж беремося за дуже важливу та цікаву тему - Флекси Основним джерелом необхідної інформації для
виконання ДЗ – конспект, відеоуроки Олександра Репети та живі вебінари з викладачем. Особливу увагу
рекомендується приділити розумінню блочної моделі - фундамент перед вивченням позиціонування. Без
розуміння цього принципу буде важко зрозуміти як технічно правильно надалі позиціонувати елементи на
сторінці незалежно від типу пристрою та його розширення. Основні моменти, на які варто звернути
увагу під час виконання ДЗ: Структуру для ДЗ берете із останньої прийнятої попередньої роботи. -->

Контейнер для контенту (div із класом container) -- це один клас для двох сторінок. Знаходиться у
кожному блоці на сторінках. Як зробити сітку карток на сторінці портфоліо - інформація є у конспекті
та у відео. Flex використовувати тільки там, де це дійсно необхідно. У нас немає фіксованої висоти.
Висота – це динамічна величина, яку задає контент. Розуміти що таке маржини та паддінги, і де їх
правильно застосовувати. Хедер має нижній бордер на обох сторінках по ширині всієї сторінки - не
забуваємо про неї. ДЗ виконується згідно з ТЗ. Код валідний форматований за допомогою prettier.
Імена класів описові. Ніяких великих букв і цифр. Властивості, що повторюються поєднуємо. Зайвий код
та непотрібні коментарі відсутні. Додаткові матеріали: Все, що потрібно знати про CSS Margin
https://habr.com/ru/post/465839/ Особливості inline-block елементів -
https://css-tricks.com/fighting-the-space-between-inline-block-elements/ Повний посібник з Flexbox -
https://css-tricks.com/snippets/css/a-guide-to-flexbox/ Гра по Flexbox -
http://flexboxfroggy.com/#ru

Хедер, секції та футер ставляться один на одного, як цегла. Поміж їхніх меж немає відступів.
Маржінів між секціями на макеті немає. Відступи по 94рх - це ПАДІНГИ.

<!-- Контейнер (це негласне правило
так називати) – один універсальний клас для всього сайту. Він завжди є в середині секції. Його
основна мета – обмежити по ширині та горизонтально вирівняти (відцентрувати) контент. Верхніх і
нижніх маржинів/паддінгів зазвичай йому не задають. Тому вміст хедера, футера та кожної з секцій має
бути обернений у дів-контейнер із шириною 1200рх та горизонтальними падінгами по 15рх.  -->

<!-- Хедер – великий смисловий елемент, як і секція. У ній є невелика особливість. Є практика, коли його
висоту задають падінгами посилань. Тобто прийнято посилання оформляти з вертикальними падінгами. -->

Так, збільшивши площу посилання, ми тільки збільшуємо шанс, що користувач клікне в неї без проблем
:нервный_смех: Секція ЗАВЖДИ на 100% ширини екрану (безмежна). Саме їй задаються падінги верхні та
нижні, якими створюються межі для контенту.

Саме секції задається фон, тому що він завжди на 100% ширини екрану. Картинки обовязково мають
обмеження по ширині. Батьківський елемент має відштовхувати від себе свій контент (вкладені
елементи/ дітей) своїми падінгами. А ось діти між собою відштовхуються маржинами, але так, щоб вони
не випадали з батьківського елемента. Для використання маржинів намагайтеся дотримуватися напряму по
потоку – правий та нижній. Це не залізне правило, просто так простіше на початковому етапі. І
простіше фіксувати та шукати неточності візуально, максимально швидко знаходячи їх у девтулзах Не
забувайте задавати елементам списків (<li>) у секціях ширину. При цьому замість властивості
justify-content: space-between більш надійним варіантом буде задати відступи між елементами списку
за допомогою маржинів (крайні відступи не забуваємо обнуляти). Для тега img задаємо властивості img
{ display: block; max-width: 100%; height: auto; } Елементам, для яких це потрібно, задаємо бордери
(наприклад, хедеру, карткам в секції портфоліо). Нижню частину карток із членами команди та карток
портфоліо (елементи під зображенням) доречно огорнути у дів, якому задати падінги з усіх боків, щоб
відштовхнути контент, тобто за таким прикладом

<img/> 
<div>
  <h3></h3>
  <p></p>
</div>
Фіксовану висоту (властивість height) текстовим елементам та елементам li не задаємо.
У деяких елементів можуть бути дефолтні, застосовані браузером, маржини та падінги, які візуально схожі за розмірами на ті, які вам потрібні (наприклад, у заголовків або абзаців). Але на це сподіватися не варто: все, що за дефолтом, обнуляємо, і задаємо відступи явно - у тих випадках і в тому розмірі, в яких нам потрібно.
Ну і, зрозуміло, уважно читаємо ТЗ
