### Домашнее задание 2

В ДЗ №2 нужно будет сделать следующее:
1) Взять реализацию KNN из семинара №3. Добавить туда возможность поиска ближайших соседей не по евклидову расстоянию, а по манхеттанскому и по косинусному. - **2 балла**
2) Взять реализацию Линейной регрессии из семинара №4 и добавить туда возможность использовать в качестве loss функции Huber Loss (https://en.wikipedia.org/wiki/Huber_loss)
Необходимо реализовать новый подсчет градиента, и добавить в класс возможность выбора Loss функции - **4 балла**
3) Взять реализацию Логистической регрессии из семинара №5 и добавить туда возможность использования L1 и L2 регуляризаций. Управляться они должна через соответвующие аргументы инициализации (penalty - для выбора типа регуляризации, C - для измения силы регуляризации (чем больше, тем регуляризация слабее)). C - гиперпарарметр модели, на который делится сама регуляризация при объединении с Lоss функцией. (Очевидно вы должны пересчитывать градиенты)- **4 балла** 


Требования:
1. Использовать собственные реализации, а не sklearn
2. Сдать необходимо в ipynb формате
3. Показать, что все работает на данных из семинаров.