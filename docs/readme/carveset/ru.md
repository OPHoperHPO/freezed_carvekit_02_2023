# Набор данных CarveSet V2.0

Мы собрали обширный набор данных, охватывающий наиболее распространенные классы объектов, 
предназначенных для удаления фона.

## Характеристики:
Он включает фотографии объектов, принадлежащих 9 различным классам.
### Распределение классов объектов в наборе данных CarveSet V2.0:

| Класс объектов                | Кол-во изображений |
|-------------------------------|--------------------|
| 🚗 автомобили                 | 1878               |
| 👗 одежда                     | 1840               |
| 🏠 предметы быта              | 1878               |
| 📱 электроника                | 1806               |
| 🧸 детские игрушки            | 1785               |
| 🍳 кухонные принадлежности    | 1878               |
| 👨‍👩‍👧‍👦 люди              | 1777               |
| 🏡 объекты в жилых помещениях | 1777               |
| 🐾 животные                   | 1878               |

Общее количество изображений в наборе данных: **16 497**.

### Разбивка на выборки:

-   Тестовая выборка: **2000** пар изображений.
-   Валидационная выборка: **2000** пар изображений.
-   Тренировочная выборка: **12 497** пар изображений.

###  Информация о базе изображений в наборе данных
1.  **CarveSet** - содержит 3 172 изображения высокого качества размером примерно 2500x2500 пикселей, собранных вручную из [Pexels](https://www.pexels.com/), [Unsplash](https://unsplash.com/).
2.  **SOPG** - состоит из 13 325 изображений, увеличенных в 4 раза из набора данных [SOPG](https://huggingface.co/datasets/absinc/sopg), 
размером примерно 2048x1536 пикселей.

## Файловая структура набора данных
-   `carveset2` - База изображений.


-   `carveset2/train` - Тренировочная выборка.
-   `carveset2/train/images` - RGB изображения.
-   `carveset2/train/masks` - Маски.
-   `carveset2/train/trimaps` - Тримапы.


-   `carveset2/val` - Валидационная выборка.
-   `carveset2/val/images` - RGB изображения.
-   `carveset2/val/masks` - Маски.
-   `carveset2/val/trimaps` - Тримапы.


-   `carveset2/test` - Тестовая выборка.
-   `carveset2/test/images` - RGB изображения.
-   `carveset2/test/masks` - Маски.
-   `carveset2/test/trimaps` - Тримапы.


-   `carveset2/train.csv` - Таблица с путями и лицензиями для RGB изображений.
-   `carveset2/val.csv` - Таблица с путями и лицензиями для RGB изображений.
-   `carveset2/test.csv` - Таблица с путями и лицензиями для RGB изображений.
-   `licenses/*.txt` - Текст лицензий
-   `terms_of_use.pdf` - Условия использования

## Лицензии
1. RGB изображения
   1. [Pexels License](https://www.pexels.com/ru-RU/license/)  - `pexels` в таблицах
   2. [Unsplash License](https://unsplash.com/license) - `unsplash` в таблицах
   3. [SOPG MIT License](https://huggingface.co/datasets/absinc/sopg#license)  - `mit` в таблицах
2. Разметка - [Apache License 2.0](https://github.com/OPHoperHPO/freezed_carvekit_2023/blob/master/LICENSE)

Подробнее о лицензиях можно прочитать в [terms_of_use.pdf](terms_of_use.pdf).
## Скачать:
Набор данных предоставляется на [специальных условиях использования.](terms_of_use.pdf)
Скачивая и используя набор данных, вы соглашаетесь с условиями использования.

 [Скачать с HuggingFace](https://huggingface.co/datasets/Carve/carveset)

 [Скачать файл (carveset2.zip)](https://huggingface.co/datasets/Carve/carveset/blob/main/carveset2.zip)