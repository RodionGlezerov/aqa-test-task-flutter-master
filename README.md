# Тестовое задание

Необходимо реализовать E2E и Widget тесты для данного приложения по ниже описанным тест кейсам.
Для E2E теста предусмотреть несколько разных вариантов поиска виджетов - byKey, byWidgetPredicate, byType и тд

## E2E test (обязательно)
<b>preconditions:</b><br>
пользователь находится на стартовом экране и видит две кнопки “зеленый”, “желтый”<br>
<b>steps:</b>
1. тапнуть на “зеленый” - должен открыться экран с белой надписью “зеленый экран” и зеленым фоном
2. тапнуть кнопку назад - должны попасть на стартовый экран
3. тапнуть на “желтый” - должен открыться экран с кнопкой “случайное число”, текст в центре экрана не отображается
4. тапнуть кнопку “случайное число” - отображается надпись с числом от 0 до 99 в центре экрана
5. тапнуть кнопку назад - должны попасть на стартовый экран

## Widget test (будет плюсом)
<b>preconditions:</b><br>
создать инстанс виджета желтого экрана<br>
<b>steps:</b>
1. должна отображаться кнопка “случайное число”, фон экрана желтый, а также должна отображаться кнопка “назад”
2. тапнуть по кнопке “случайное число” и проверить, что число от 0 до 49 отображается синим цветом


# Test Task

You need to implement E2E and Widget tests for this application according to the test cases described below.
For E2E test provide several different widget search options - byKey, byWidgetPredicate, byType, etc.

## E2E test
prerequisites:
user is on the start screen and sees two buttons "green", "yellow"
steps:
1. Tap on the "green" button to bring up a screen with a white "green screen" caption and a green background
2. Tap the back button to return to the start screen.
3. tap on "yellow" - a screen with a "random number" button should open, the text in the middle of the screen is not displayed
4. tap the button "random number" - the inscription with the number from 0 to 99 in the center of the screen is displayed
5. tap the back button - should go back to the start screen

## Widget test
preconditions:
create yellow screen widget instance
steps:
1. The "random number" button should be displayed, the screen background yellow, and the "back" button should be displayed
2. Click on the "random number" button and check that the number between 0 and 49 is displayed in blue
