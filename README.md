# Arch Clasification

Обучено несколько CV моделей для классификации изображений зданий.
Цель: определить принадлежность строения к одному из архитектурных стилей.

- В данном ноутбуке проведено несколько экспериментов с предобученной на имаженете готовой моделью
- По итогам получить достаточного скора не получилось. Максимальный  accuracy  = 0.54 на валиде.
- Это неудивительно ведь данных мало, а аугментация сложная.


Данные взяты отсюда [ADrepo](https://github.com/msand67/ADrepo)

Проект на стадии разработки. Планируется реализовать сервис с возможностью загружать изображение и получать предсказание.
Дополнительные ручные данные, сейчас на стадии разметки. Идея заключается в будущем не только классифицировать стили, но и определять коэффициент "Архитектурных излишеств" - то есть определять некую метрику совокупного количества архитектурных украшений на здании.

