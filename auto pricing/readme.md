**!** Если проект **не открывается**, можно [перейти по ссылке](https://nbviewer.jupyter.org/github/aazaozerskaia/YaPraktikum/blob/main/auto%20pricing/%D1%86%D0%B5%D0%BD%D0%BE%D0%BE%D0%B1%D1%80%D0%B0%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%B0%D0%B2%D1%82%D0%BE.ipynb)


**Задача** - построить модель для определения стоимости авто

**Ключевые шаги**  
1. Предобработка данных
2. Подготовка признаков
3. Построение моделей
4. Тестирование

**Описание**  
Сервис по продаже подержанных авто разрабатывает приложение, в котором можно быстро узнать рыночную стоимость автомобиля. Предоставлены исторические данные: технические характеристики, комплектации и цены. Необходимо построить модель для определения стоимости с учётом важности качества предсказания и скорости предсказания и обучения.

**Вывод**  
На основе проанализированных данных, было построено несколько моделей. Наиболее точной оказалась lightgbm. Сравнение моделей предлагалось сделать с помощью RMSE. Для всех моделей наиболее важными признаками оказались год регистрации, мощность и бренд авто.


**Библиотеки**  
pandas, numpy, matplotlib, sklearn, catboost, lightgbm




