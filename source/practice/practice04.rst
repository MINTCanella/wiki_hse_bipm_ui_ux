4. Переменные размеров и автолейауты
==============================================

Дата проведения
---------------
26.11.2024

Задание
-------

1. Добавьте размеры в виде переменных (по аналогии с палитрами).
   Все размеры создавайте в той же коллекции, где и цвета.

   Пример имени размера: Size/2.
   Имя = размер.

   Список размеров:
   0, 2, 4, 6, 8, 12, 16, 20, 24, 28, 32

2. На странице Screens создайте **15 автолейаутов**.

   Цвет фона автолейаута — Base/0,
   Цвет элементов выбирайте самостоятельно из любых имеющихся переменных.

   Каждый автолейаут должен содержать **2 квадрата** размерами 24 на 24 пикселя.

   Если не указан ресайз элементов, то по умолчанию fixed.

   Все числовые значения обязательно указывайте с помощью переменных.

1.

   - Direction: vertical
   - Alignment: left center
   - Gap: 4
   - Padding top and bottom: 8
   - Padding left and right: 8

2.

   - Direction: vertical
   - Alignment: center
   - Gap: 8
   - Padding top and bottom: 16
   - Padding left and right: 16

3.

   - Direction: horizontal
   - Alignment: bottom
   - Gap: 4
   - Padding top and bottom: 4
   - Padding left and right: 4
   - Resize: Both elements horizontal fill container

4.

   - Direction: vertical
   - Alignment: left bottom
   - Gap: 8
   - Padding top and bottom: 4
   - Padding left and right: 4

5.

   - Direction: horizontal
   - Alignment: center
   - Gap: 16
   - Padding top and bottom: 8
   - Padding left and right: 8

6.

   - Direction: vertical
   - Alignment: right center
   - Gap: 6
   - Padding top and bottom: 12
   - Padding left and right: 12

7.

   - Direction: horizontal
   - Alignment: center
   - Gap: auto
   - Padding top and bottom: 24
   - Padding left and right: 12

8.

   - Direction: vertical
   - Alignment: bottom center
   - Gap: 12
   - Padding top and bottom: 20
   - Padding left and right: 20
   - Resize: Both elements vertical and horizontal fill container

9.

   - Direction: horizontal
   - Alignment: right center
   - Gap: 4
   - Padding top and bottom: 0
   - Padding left and right: 0
   - Resize: Both elements horizontal fill container

10.

   - Direction: vertical
   - Alignment: left top
   - Gap: 4
   - Padding top and bottom: 4
   - Padding left and right: 4

11.

   - Direction: horizontal
   - Alignment: right bottom
   - Gap: 16
   - Padding top and bottom: 16
   - Padding left and right: 16
   - Resize: One element horizontal fill container, the other fixed width

12.

   - Direction: vertical
   - Alignment: right top
   - Gap: 32
   - Padding top and bottom: 8
   - Padding left and right: 8

13.

   - Direction: vertical
   - Alignment: center top
   - Gap: 8
   - Padding top and bottom: 4
   - Padding left and right: 12
   - Resize: Both elements vertical fill container

14.

   - Direction: horizontal
   - Alignment: center top
   - Gap: 8
   - Padding top and bottom: 24
   - Padding left and right: 24
   - Resize: Both elements horizontal fill container

15.

   - Direction: horizontal
   - Alignment: left bottom
   - Gap: 4
   - Padding top and bottom: 32
   - Padding left and right: 16

Рекомендации по выполнению
--------------------------

- Для переменных размеров используйте одинаковую структуру именования, чтобы легко было ориентироваться при дальнейшей работе с компонентами.
- Все значения (gap, padding...) обязательно в дальнейшем берите из заранее созданных переменных.
- При создании автолейаутов внимательно следите за направлением, выравниванием и поведением элементов — это поможет избежать ошибок в верстке.
- Используйте разные цвета элементов, чтобы визуализировать итоги практики.