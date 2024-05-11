# Определение возраста покупателей
<a href='https://github.com/mr-lexx/Yandex_Practicum/blob/main/Determining_age/TFkeras.html'>HTML</a> | 
<a href='https://github.com/mr-lexx/Yandex_Practicum/blob/main/Determining_age/TFkeras.ipynb'>ipynb</a>

## Описание проекта
Сетевой супермаркет «Хлеб-Соль» внедряет систему компьютерного зрения для обработки фотографий покупателей. Фотофиксация в прикассовой зоне поможет определять возраст клиентов, чтобы:<br>
- Анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы;
- Контролировать добросовестность кассиров при продаже алкоголя.
<br>
Постройте модель, которая по фотографии определит приблизительный возраст человека. В распоряжении набор фотографий людей с указанием возраста.

## Навыки и инструменты
- **pandas**
- **numpy**
- tensorflow.keras.preprocessing.image.**ImageDataGenerator**
- tensorflow.keras.layers.**Conv2D**
- tensorflow.keras.layers.**Flatten**
- tensorflow.keras.layers.**Dense**
- tensorflow.keras.layers.**AvgPool2D**
- tensorflow.keras.layers.**MaxPooling2D**
- tensorflow.keras.layers.**GlobalAveragePooling2D**
- tensorflow.keras.models.**Sequential**
- tensorflow.keras.optimizers.**Adam**
- tensorflow.keras.applications.resnet.**ResNet50**
  

## Общий вывод 
Возрастной промежуток покупателей составил от 1 до 100 лет. Построив график распределения, было обнаружено, что данное распределение неравномерное и большая часть фотографий соответствовала возрастной категории 20-41 год. Имеются просадки в категории 8-12 лет, а также спрад после 26 лет с некоторыми "всплесками". Были выведены несколько произвольных фотографии для проверки адекватности предоставленных данных. В качестве модели машинного обучения была выбрана Resnet50, которая позволила добиться заданной точности MSE <7. Общее время обучения модели заняло порядка 10 минут.

## Статус проекта
Завершён
