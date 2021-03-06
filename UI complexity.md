# Оценка сложности UI  

## Оценка сложности разработанного приложения  

### Таблица сумарного количества действий

|   | Создание питомца | Создание события | Добавление кведомления о событии | Просмотр события на следующий месяц | Удаление и переход к редактированию события | Выполнение события | Смена питомца | Прохождение опроса |Просмотр статистики |
|---|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|:------:|
|Клик | 7 | 6 | 3 | 1 | 2 | 1 | 3 | 4 | 3 |
|Двойной клик | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
|Долгое нажатие | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 |
|Свайп | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 |
|Выбор | 4 | 2 | 2 | 0 | 0 | 0 | 0 | 1 | 1 | 
|Ввод текста | 1 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
|Ожидание | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
|Физические кнопки | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
|Всего| 12 | 9 | 5 | 2 | 3 | 1 | 3 | 5 | 4 |  

### Последовательности взаимодействия  
#### 1. Создание питомца   
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 7 | 0 | 0 | 0 | 4 | 1 | 0 | 0 | 12 |    


![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/1.png)   

Примечание: 3 клика обусловлены необходимостью нажатия при выборе вида питомца, года и месяца его рождения
#### 2. Создание события
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 6 | 0 | 0 | 0 | 2 | 1 | 0 | 0 | 9 |  

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/2.png)   

Примечание: 1 клик добавляется при нажатии кнопки "Ввод" на клавиатуре после ввода текста события, еще 1 клик обусловлен необходимостью нажатия при выборе повторения события  

#### 3. Добавление уведомления о событии  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 3 | 0 | 0 | 0 | 2 | 0 | 0 | 0 | 5 |    

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/3.png)   

#### 4. Просмотр события на следующий месяц  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 1 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 2 |  

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/9.png)

#### 5. Удаление и переход к редактированию события  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 2 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 3 |    

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/4.png)  

#### 6. Выполнение события  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 |    

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/5.png)  

#### 7. Смена питомца  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 3 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 3 |    

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/6.png)  

#### 8. Прохождение опроса  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 4 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 5 |    

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/7.png)  

Примечание: 1 клик обусловлен необходимостью нажатия при выборе дня опроса  

#### 9. Просмотр статистики  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 3 | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 4 |    

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/8.png)  

Примечание: 1 клик обусловлен необходимостью нажатия при выборе месяца  

## Возможные варианты улучшения  

1. При долгом нажатии на событие переход в режим редактирования события, в котором имеется возможность удаления события. Таким  образом возможно избавиться от одного перехода по экранным формам.   

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/10.png)    

2. Выпадающий список для смены питомца на главном экаране. Таким образом возможно избавиться от переходов по экранным формам, так как для смены питомца не нужно будет переходить к параметрам.  

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/11.png)   

## Оценка сложности для ближайшего аналога "Дневник питомца"  

### Таблица сумарного количества действий

|   | Создание питомца | Создание события | Добавление кведомления о событии | Просмотр события на следующий месяц | Удаление и переход к редактированию события | Выполнение события | Смена питомца | 
|---|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|
|Клик | 5 | 7 | 6 | 2 | 4 | 1 | 0 |
|Двойной клик | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
|Долгое нажатие | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 
|Свайп | 0 | 0 | 0 | 1 | 0 | 0 | 1 |
|Выбор | 0 | 2 | 4 | 0 | 0 | 0 | 0 | 
|Ввод текста | 1 | 1 | 0 | 0 | 0 | 0 | 0 |
|Ожидание | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 
|Физические кнопки | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
|Всего| 6 | 10 | 10 | 3 | 4 | 1 | 1 |   

### Последовательности взаимодействия  
#### 1. Создание питомца   
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 5 | 0 | 0 | 0 | 0 | 1 | 0 | 0 | 6 | 

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/12.png)   

#### 2. Создание события
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 7 | 0 | 0 | 0 | 2 | 1 | 0 | 0 | 10 |

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/13.png)  

#### 3. Добавление уведомления о событии  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 6 | 0 | 0 | 0 | 4 | 0 | 0 | 0 | 10 |    

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/14.png)  

#### 4. Просмотр события на следующий месяц  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 2 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 3 |  

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/15.png)    

#### 5. Удаление и переход к редактированию события  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 4 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 |    

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/16.png)

#### 6. Выполнение события  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 |    

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/17.png)  

#### 7. Смена питомца  
| Клик | Двойной клик | Долгое нажатие | Свайп | Выбор | Ввод текста | Ожидание | Физические кнопки | Всего |
|:---:|:-----------------:|:-------------:|:---------------:|:-----------:|:------:|:------:|:------:|:------:|
| 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 1 |    

![](https://github.com/AngelinaKalyaeva/1-2019/blob/master/18.png)
