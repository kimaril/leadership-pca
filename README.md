# PCA for leadership project

Запустить ноутбук в **Binder**:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kimaril/leadership-pca/master)

Принцип работы метода хорошо описан здесь: https://habr.com/ru/post/304214/

Количество "групп" в данных при каждом запуске PCA равно параметру n_components. Собственное значение матрицы ковариации, соответствующее каждой компоненте, можно считать показателем важности этой группы в наших данны - чем больше это значение, тем больше разброса в данных мы потеряем, если уберем эту группу. Сохранение variance данных - основное ограничение PCA.

Каждому собственному значению соответствует собственный вектор. Каждый его элемент указывает на то, как коррелированы принадлежность объекта к это
