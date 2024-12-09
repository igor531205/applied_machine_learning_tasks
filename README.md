# [hw1_supervised_learning.ipynb](https://github.com/igor531205/applied_machine_learning_tasks/blob/main/hw1_supervised_learning.ipynb) - Домашнее задание №1:
* Найти датасет для классификации на kaggle.com
* Выполнить разведочный анализ и визуализацию данных: построить распределения переменных, найти выбросы
* Применить все описанные методы классификации, сравнить их точность (метрика accuracy)
* Применить все описанные методы регрессии, сравнить их точность (метрика rmse)
* Сделать выводы
* Полезная библиотека: https://scikit-learn.org/

# [hw2_hyperparameters_and_metrics_ml.ipynb](https://github.com/igor531205/applied_machine_learning_tasks/blob/main/hw2_hyperparameters_and_metrics_ml.ipynb) - Домашнее задание №2:
* Добавить в решение ДЗ№1 8 дополнительных метрик классификации и регрессии
* Использовать поиск по сетке и подбор оптимальных признаков для оценки качества
* Добиться хорошего качества классификации и регрессии на всех моделях

# [hw3_vector_quantization.ipynb](https://github.com/igor531205/applied_machine_learning_tasks/blob/main/hw3_vector_quantization.ipynb) - Домашнее задание №3:
* Собрать датасет, прогнав любую (какой-нибудь BERT) модель на любом датасете (~10k строк) или сгенерировав данные самостоятельно с каким-то известным распределением (не полностью случайно)
* Квантизовать: разбить каждый вектор на 4 под-вектора, внутри пространств под-векторов (получается 4 пространства, в каждом кластеризуем на 16 кластеров) провести кластеризацию любым библиотечным методом, собрать codebook
* Для нескольких векторов прогнать алгоритм: вектор -> квантизованный_вектор (индексы) -> восстановленный_вектор -> абсолютная_ошибка_представления -> относительная_ошибка_представления
* Вывести codebook для ручной проверки
* Определить среднюю ошибку представления на датасете, сделать вывод о качестве модели

# [hw6_torch_quickstart.ipynb](https://github.com/igor531205/applied_machine_learning_tasks/blob/main/hw6_torch_quickstart.ipynb) - Домашнее задание №6:
* Выбрать датасет с картинками
* Выбрать архитектуру модели из списка (https://paperswithcode.com/sota/image-classification-on-imagenet)
* Написать и прогнать Training Loop на несколько эпох
* Посчитать метрику accuracy 
* Вывести несколько рандомных предсказаний и реальные лейблы
