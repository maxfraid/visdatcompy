![](static/logo.png)

## Библиотека для сравнения визуальных наборов данных.

## Используемые библиотеки:

-   Pillow - https://pypi.org/project/pillow/
-   Scikit Learn - https://pypi.org/project/scikit-learn/
-   NumPy - https://pypi.org/project/numpy/
-   Pandas - https://pypi.org/project/pandas/
-   Colorama - https://pypi.org/project/colorama/

<!-- = = = = = = = = = = = = = = = = = = = = = = = = = ИНФА ПРО МЕТРИКИ И ИХ СРАВНЕНИЕ = = = = = = = = = = = = = = = = = = = = = =  -->

<!-- #### 1. Pix2Pix:
    a) Самая большая скорость работы
    b) Распознает только абсолютно одинаковые изображения
    c) Не требует дополнительных библиотек кроме Pillow и Numpy
#### 2. MSE:
    a) Высокая скорость работы
    b) На изображениях со схожими тенями постройки показатели сходятся с показателями на изображениях без этой тени
#### 3. NRMSE
    a) Время работы больше чем MSE
    b) На изображениях со схожими тенями заметно меньше показатель(большее сходство изображений)
#### 4. SSIM
    a) Время работы еще больше чем NRMSE
    b) У изображений с похожей тенью одинаково больше показатель чем у двух прочих
#### 5. PSNR
    a) Время работы наравне с NRMSE
    b) Большой диапазон значений, большая разница в сравнении
#### 6. MAE
    a) Высокая скорость работы, немного дольше P2P
    b) На изображениях с видимым сходством наоборот значение более высокое. Возможно сравнивает по нестандартным значениям.
#### 7. NMI
    a) Время работы незначительно больше NRMSE
    b) Примерно одинаковые значения при сравнении (при значениях в три знака после запятой), возможно более детализированное сравнение.
#### 5. FSIM
    a) Большое время выполнения
    b) У отличающихся изображений схожий показтель
#### 6.	SRE
    a) Небольшое время выполнения
    b) Схожий показатель для разных изображений
#### 7.	SAM
    a) Небольшое время выполнения
    b) Показатели почти полностью одинаковые(даже при сравнении с таким же изображением)
#### 8.	UIQ
    a) Очень долгое время выполнения( в несколько раз больше чем у fsim)
    b) Для других изображений показатели около 0, возможно требуется сравнивать одинаковое изображение разного качества -->
