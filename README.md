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

# [hw5_aggregation_of_assessments.ipynb](https://github.com/igor531205/applied_machine_learning_tasks/blob/main/hw5_aggregation_of_assessments.ipynb) - Домашнее задание №5:
* Сгенерировать датасет асессорских оценок вида (task, worker, label)
* Построить графики распределений
* Запустить на датасете алгоритмы DawidSkene и MajorityVote из библиотеки crowd-kit
* Проанализировать расхождения алгоритмов на конкретных примерах
* Выделить самый частый кейс, в котором DawidSkene и MajorityVote будут расходиться

# [hw6_torch_quickstart.ipynb](https://github.com/igor531205/applied_machine_learning_tasks/blob/main/hw6_torch_quickstart.ipynb) - Домашнее задание №6:
* Выбрать датасет с картинками
* Выбрать архитектуру модели из списка (https://paperswithcode.com/sota/image-classification-on-imagenet)
* Написать и прогнать Training Loop на несколько эпох
* Посчитать метрику accuracy 
* Вывести несколько рандомных предсказаний и реальные лейблы

# [hw7_torch_techniques.ipynb](https://github.com/igor531205/applied_machine_learning_tasks/blob/main/hw7_torch_techniques.ipynb) - Домашнее задание №7:
* Добавить в hw6 Итеративную аугментацию
* Итеративную разморозку слоев
* Псевдолейблинг
* Дистилляцию
