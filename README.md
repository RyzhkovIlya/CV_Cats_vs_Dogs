# CV_Cats_vs_Dogs
## Задача
Создать нейронную сеть, способную по фотографии отличать кошку от собаки
## Этапы реалтзации задачи
1) Загружаем датасет с сайта microsoft.com  и убираем битые фотографии;
2) Создаем генератор фотографий на train и valid выборке и проводим аугментацию;
3) Создаем HistoryCallback для дальнейшего вывода графиков;
4) Загружаем и проверяем предобученные модели ResNet50 и DenseNet121;
5) Создаем свою нейронную сверточную сеть с конечным полносвязным слоем с функцией активации - sigmoid;
6) Обучаем полученную модель, выводим предсказания и графики.
## Выводы
По итогам обучения трех моделей, наилучший результат на валдационной выборке показала моель ResNet50, далее наша собственная модель,и худший результат показала модель DenseNet121.
## Проеверка работосположности кода
Запустить поочереди все строчки кода.
