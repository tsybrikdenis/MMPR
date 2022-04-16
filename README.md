# Математические методы распознавания образов 
Лабораторные работы для универа на Python без использования ML-библиотек 
## Л.1 Модель нейрона для классификации 
Дана обучающая выборка:

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>x1</th>
      <th>x2</th>
      <th>answer</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>1.0</td>
      <td>1.0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>2</th>
      <td>9.4</td>
      <td>6.4</td>
      <td>-1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2.5</td>
      <td>2.1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>4</th>
      <td>8.0</td>
      <td>7.7</td>
      <td>-1</td>
    </tr>
    <tr>
      <th>5</th>
      <td>0.5</td>
      <td>2.2</td>
      <td>1</td>
    </tr>
    <tr>
      <th>6</th>
      <td>7.9</td>
      <td>8.4</td>
      <td>-1</td>
    </tr>
    <tr>
      <th>7</th>
      <td>7.0</td>
      <td>7.0</td>
      <td>-1</td>
    </tr>
    <tr>
      <th>8</th>
      <td>2.8</td>
      <td>0.8</td>
      <td>1</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1.2</td>
      <td>3.0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>10</th>
      <td>7.8</td>
      <td>6.1</td>
      <td>-1</td>
    </tr>
  </tbody>
</table>

Найти уравнение прямой, которая делит точки на два класса.
Дополнительно: Анимировать процесс обучения. 
## Л.2 Решающие деревья 
Даны точки принадлежащщие двум классам, найти решающее дерево.

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>x_1</th>
      <th>x_2</th>
      <th>x_3</th>
      <th>x_4</th>
      <th>x_5</th>
      <th>answer</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>k_1</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>k_1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>k_1</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>k_1</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>k_1</td>
    </tr>
    <tr>
      <th>6</th>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>k_2</td>
    </tr>
    <tr>
      <th>7</th>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>k_2</td>
    </tr>
    <tr>
      <th>8</th>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>k_2</td>
    </tr>
    <tr>
      <th>9</th>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>k_2</td>
    </tr>
    <tr>
      <th>10</th>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>k_2</td>
    </tr>
  </tbody>
</table>

### 1. D-критерий 
Использовать D - критерий 
### 2. Энтропийный критерий (С4.5)
Использовать энтропийный критерий 
## Л.3 Кластеризация 
Дано пространство объектов, обучающая выборка, функция расстояний между объектами.
Найти множество кластеров и алгоритм кластеризации такие, что: 
- каждый кластер состоит из близких объектов
- объекты разных кластеров существенно различны 
### 1. Агломеративная иерархическая кластеризация
### 2. K-means 
## Л.4 Генетический алгоритм для Диофантового уравнения 

