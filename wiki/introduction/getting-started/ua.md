# Початок роботи з Quilt

## Базові вимоги

Щоб почати створювати моди для Minecraft, потрібно знати кілька речей:

- **Базові знання Java**. Сюди входить розуміння синтаксису мови, об’єктно-орієнтованого програмування та деяких основних шаблонів проєктування.
- **Базові знання [Git](https://git-scm.com/)**. Технічно це не обов’язково, але значно полегшить тобі життя. Сюди входить розуміння того, як клонувати репозиторії та робити коміти. Чудові ресурси: [документація Git](https://git-scm.com/doc) та [документація GitHub](https://docs.github.com/en/get-started).

<!-- TODO: Чи потрібно тут ще щось описати? -->

## Як користуватися цією вікі

<!-- TODO: Створити прикладовий репозиторій з кодом і додати сюди (див. [Issue #68](https://github.com/QuiltMC/developer-wiki/issues/68)) -->

Ця вікі складається зі сторінок, які найкраще читати послідовно. Багато статей, особливо на початку, радять подальші матеріали, які логічно прочитати наступними. Більшість сторінок містять фрагменти коду. Повні приклади планується додати у вигляді прикладових модів (ще не реалізовано).

У наступній статті ти налаштуєш свій перший мод, щоб почати розробку.

Після цього рекомендується прочитати [Створення вашого першого предмета](../items/first-item). Далі можна переходити до [додавання блоків](../blocks/first-block) або створення складніших предметів, наприклад: [їжа](../items/food), [інструменти](../items/tools) і [броня](../items/armor).

Для загальнішого розуміння можна перейти до розділу "Концепції":

- У [Огляд QSL і QFAPI](../concepts/qsl-qfapi) ти знайдеш інформацію про Quilt Standard Libraries та Quilted Fabric API — офіційні API Quilt.

Багато інших статей плануються, але ще не написані ([Issue #69](https://github.com/QuiltMC/developer-wiki/issues/69)). Цей розділ буде оновлюватися.

<!-- TODO: Додати зміст усіх статей вікі, щойно вони будуть готові -->

## Як вивчати моддинг для початківців

Моддинг Minecraft може бути складним. Ми прагнемо створити ресурс, який допоможе тобі вивчити базові концепції моддингу. Але є речі, які ти маєш вивчити самостійно.

Не бійся ставити запитання — ми завжди раді допомогти та не засуджуємо.

Коли ставиш запитання, намагайся одразу вказати весь потрібний контекст: опиши проблему, що ти вже пробував і що не спрацювало. Повний контекст дозволяє швидше знайти рішення. Якщо щось не працює — додай файл `latest.log`, а в разі крашу — лог крашу. Також дуже корисно надати доступ до свого коду, бажано через GitHub.

Ставити питання можна на нашому [форумі](https://forum.quiltmc.org/), а також у каналі [mod-dev-help](https://discord.com/channels/817576132726620200/1047429688521396325) на нашому [Discord-сервері](https://discord.quiltmc.org/)

Більшість проблем у моддингу вже були вирішені раніше, і ти можеш побачити їх рішення у відкритому доступі — більшість модів для Quilt є відкритими. Ми радимо переглядати код інших модів і навіть "красти" зразки рішень — відкриті репозиторії створені саме для того, щоб на них вчитися. Не бійся їх!

Є багато тем у моддингу, на які ще немає гідних туторіалів. У таких випадках тобі, можливо, доведеться заглядати в код Minecraft або переглядати, як інші моди реалізували подібні ідеї. І знову ж — не бійся просити допомогу, коли щось незрозуміло.

Щоб переглядати вихідний код Minecraft, запусти задачу Gradle `genSourcesWithVineflower` у категорії `fabric`, або просто відкрий будь-який файл з кодом Minecraft у IntelliJ IDEA й натисни кнопку "завантажити джерела".

<!-- TODO: Чи цей todo уже неактуальний?: Levi, напиши сюди свій текст про крадіжку коду -->
