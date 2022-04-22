# <img src="https://user-images.githubusercontent.com/64004682/154757110-4c4c0206-27c1-427b-a04e-a070a01b381f.png" alt="icon" width="30"/> ColorConverter
Компьютерная графика. Лабораторная работа №1.


## Задача
Изучить цветовые модели: RGB, CMYK, HSV, HLS, XYZ, LAB, переход от одной модели к другой, исследовать цветовой график МКО.

Создать приложение/веб-приложение, позволяющее пользователю выбирать, а затем интерактивно менять цвет, показывая при этом его составляющие в трех моделях одновременно.

## На проверку сдаются
* exe, который должен работать на ПК преподавателя под Windows/веб-приложение, размещенное в общем доступе;
* исходный код приложения на gitHub;
* сопроводительная документация.

## Основные требования к приложению
В интерфейсе дать возможность пользователю задавать точные цвета (поля ввода), выбирать цвета из палитры (аналогично графическим редакторам), плавно изменять цвета (например, ползунки).

При изменении любой компоненты цвета все остальные представления этого цвета в двух других цветовых моделях пересчитываются автоматически. При «некорректных цветах» (например, при переходе из XYZ в RGB в вашем расчете получился выход за границы изменения рассчитываемого параметра) выдавать некое ненавязчивое предупреждение, что происходит обрезание-округление и т.п.

## Вариант 18
CMYK - XYZ - RGB

## Реализация
<p align="center">
  <kbd> <img alt="ColorConverter_1" src="https://user-images.githubusercontent.com/64004682/154757203-5722eb51-97fe-444b-9316-79842683c2dd.png" width="1000" style="border-radius:10px"\></kbd> 
</p>
<p align="center">
  <kbd> <img alt="ColorConverter_2" src="https://user-images.githubusercontent.com/64004682/154757263-2e20d93c-c8c6-4b07-9cf6-26bfc5d74a9d.png" width="1000" style="border-radius:10px"\></kbd> 
</p>
<p align="center">
  <kbd> <img alt="ColorConverter_3" src="https://user-images.githubusercontent.com/64004682/154757199-1620e85c-d5a4-422f-9c98-0f92d1daf8a1.png"" width="1000" style="border-radius:10px"\></kbd> 
</p>
<p align="center">
  <kbd> <img alt="ColorConverter_gif" src="https://user-images.githubusercontent.com/64004682/155126030-f6af92a3-daf0-4196-98a8-14762ead8363.gif"" width="1000" style="border-radius:10px"\></kbd> 
</p>