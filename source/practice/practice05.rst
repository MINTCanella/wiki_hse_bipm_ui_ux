5. Иконки, кнопки и селекторы
=======================================

Дата проведения
---------------
03.12.2024

Задание
-------

1. С сайта pictogrammer скачайте минимум 15 иконок в формате SVG.

   Что обязательно понадобится:

   - пустой и выделенный чекбоксы и радиобоксы (всего 4 иконки),
   - три точки (more),
   - профиль (account),
   - поиск (magnify),
   - стрелки влево/вправо (arrow-left, arrow-right),
   - остальные иконки — на ваше усмотрение, по теме приложения.

   Размер иконок (24x24 px) не меняйте, название вектора Vector не переименовывайте.

   Что нужно сделать с иконками:

   - Переименовать все фреймы иконок по шаблону: `icon/<название_иконки>`
   - Выделить все иконки и в правой панели в разделе Selected colors выбрать цвет Base/6.
   - Сделать все иконки отдельными родительскими компонентами.

2. Создайте с нуля компонент Button.

   В вариациях используйте иконку поиска.

   Автолейаут в кнопках должен быть с выравниванием по центру и hug content со всех сторон.

   **Properties:**

   - Size: S, M, L
   - Type: Primary, Secondary, Tertiary
   - State: Enabled, Pressed, Disabled
   - Icon: On, Off

   **Параметры для размеров:**

   S

   - Иконки: 16x16
   - Текстовый стиль: M/Normal
   - Gap: 8
   - Left-Right: 8
   - Top-Bottom: 6

   M

   - Иконки: 16x16
   - Текстовый стиль: M/Normal
   - Gap: 12
   - Left-Right: 16
   - Top-Bottom: 12

   L

   - Иконки: 24x24
   - Текстовый стиль: L/Normal
   - Gap: 12
   - Left-Right: 20
   - Top-Bottom: 16

   **Типы:**

   **Primary**

   .. list-table::
      :widths: 15 20 20 25
      :header-rows: 1

      * - State
        - Fill
        - Stroke
        - Icon/text color
      * - Enabled
        - <главный цвет>/5
        - -
        - Base/0
      * - Pressed
        - <главный цвет>/7
        - -
        - Base/0
      * - Disabled
        - Base/3
        - -
        - Base/0

   **Secondary**

   .. list-table::
      :widths: 15 20 25 20
      :header-rows: 1

      * - State
        - Fill
        - Stroke
        - Icon/text color
      * - Enabled
        - Base/0
        - 1px, inside, Base/2
        - Base/10
      * - Pressed
        - Base/0
        - 1px, inside, Base/7
        - Base/7
      * - Disabled
        - Base/0
        - 1px, inside, Base/3
        - Base/3

   **Tertiary**

   .. list-table::
      :widths: 15 20 25 20
      :header-rows: 1

      * - State
        - Fill
        - Stroke
        - Icon/text color
      * - Enabled
        - -
        - -
        - Base/10
      * - Pressed
        - -
        - -
        - Base/7
      * - Disabled
        - -
        - -
        - Base/3

   Всего должно получиться 27 вариаций кнопки.

   После создания всех вариаций **скройте иконку по умолчанию во всех вариациях**.

3. Скопируйте в свой файл селекторы со страницы "Для практик".

   Перекрасьте селекторы, замените текстовые стили на свои, иконки чекбоксов и радиобаттонов — на свои иконки, сделайте расстояния между элементами переменными.
   Автолейауты уже настроены, их менять не нужно.

   **Checkbox**

   .. list-table::
      :header-rows: 2
      :widths: 20 20 20 20 20

      * -
        - Selected: Yes
        - Selected: Yes
        - Selected: No
        - Selected: No
      * - State
        - Icon
        - Text
        - Icon
        - Text
      * - Enabled
        - выбранный чекбокс, <главный цвет>/5
        - M/Normal, Base/10
        - пустой чекбокс, Base/5
        - M/Normal, Base/10
      * - Disabled
        - выбранный чекбокс, Base/3
        - M/Normal, Base/5
        - пустой чекбокс, Base/3
        - M/Normal, Base/5

   **Radio button**

   .. list-table::
      :header-rows: 2
      :widths: 20 20 20 20 20

      * -
        - Selected: Yes
        - Selected: Yes
        - Selected: No
        - Selected: No
      * - State
        - Icon
        - Text
        - Icon
        - Text
      * - Enabled
        - выбранный радиобаттон, <главный цвет>/5
        - M/Normal, Base/10
        - пустой радиобаттон, Base/5
        - M/Normal, Base/10
      * - Disabled
        - выбранный радиобаттон, Base/3
        - M/Normal, Base/5
        - пустой радиобаттон, Base/3
        - M/Normal, Base/5

   **Switch (круг всегда Base/0)**

   .. list-table::
      :header-rows: 2
      :widths: 20 20 20 20 20

      * -
        - Selected: Yes
        - Selected: Yes
        - Selected: No
        - Selected: No
      * - State
        - Switch fill
        - Text
        - Switch fill
        - Text
      * - Enabled
        - <главный цвет>/5
        - M/Normal, Base/10
        - Base/5
        - M/Normal, Base/10
      * - Disabled
        - Base/3
        - M/Normal, Base/5
        - Base/2
        - M/Normal, Base/5

Рекомендации по выполнению
--------------------------

- Для скачивания иконок используйте официальный сайт, выбирайте SVG-формат.
- Внимательно переименовывайте компоненты.
- Используйте переменные цветов и размеров для максимальной гибкости компонентов.

Полезные ссылки
---------------

- `Pictogrammer <https://pictogrammers.com/library/mdi/>`_ — сайт с SVG иконками