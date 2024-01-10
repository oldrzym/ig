## Обработка и генерация изображений

# Домашняя работа № 3
Калиновский Константин Сергеевич

Задача множественной классификации

Датасет CIFAR-10

В качестве бейзлайна выбрана простая модель со слоями конволюции и dense слоем на выходе

Метрики базовой модели:
![image](https://github.com/oldrzym/ig/assets/115554194/1c3c292a-cd36-425b-adf0-4371438d37d7)

# Эксперимент 1

Из графиков видно, что экспериментальная модель демонстрирует быстрое улучшение производительности на тренировочных данных, однако показывает признаки переобучения при проверке на валидационных данных: после определенного момента увеличиваются потери и стабилизируются показатели точности и полноты. В бейзлайн модели метрики улучшаются более равномерно, что свидетельствует о лучшей обобщающей способности. Это может означать, что экспериментальной модели необходимы дополнительные методы борьбы с переобучением, такие как более сильная регуляризация или расширение набора валидационных данных.
![image](https://github.com/oldrzym/ig/assets/115554194/2861e89e-6c93-4c42-8d1b-d5c3a27d2ea6)
![image](https://github.com/oldrzym/ig/assets/115554194/c454692f-e958-4549-bfda-8996a09b89ec)
