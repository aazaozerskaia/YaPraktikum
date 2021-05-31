**Задача** - построить модель классификации текстов со значением метрики качества *F1* >= 0.75. 

**Ключевые шаги**  
1. Обзор данных
2. Подготовка текстовой переменной 
3. Обучение моделей

**Описание**  
Интернет-магазин запускает новый сервис, где пользователи могут редактировать и дополнять описания товаров. Клиенты смогут предлагать правки и комментировать изменения других. Необходимо разработать инструмент, который будет искать токсичные комментарии и отправлять их на модерацию. 
Требуется разработать модель, которая будет определять комментарий позитивный или негативный. Предоставлены размеченные данные с пометкой о токсичности и тексты комментариев.

**Вывод**  
В задаче присутствовал дисбаланс классов: токсичных комментариев - 10% от выборки. Были произведены токенизация, очищение от стоп-слов, лемматизация. Преобразование переменных осуществлено с помощью TF-IDF. Сравнение моделей произведено с помощью разных метрик классификации. Разные модели отвечают разным требованиям качества.

**Библиотеки**  
pandas, sklearn, nltk, pytorch, catboost, lightgbm, matplotlib 
