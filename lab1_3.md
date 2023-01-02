## Імітаційне моделювання комп'ютерних систем
## СПм-21-2, **Сергєєв Данило Андрійович**
### Лабораторная работа №**1**. Описание имитационных моделей

<br>

### Выбранная модель в среде NetLogo:
[Doppler](http://www.netlogoweb.org/launch#http://www.netlogoweb.org/assets/modelslib/Sample%20Models/Chemistry%20&%20Physics/Waves/Unverified/Doppler.nlogo)

<br>

### Вербальное описание модели:
Doppler - эта модель демонстрирует эффект Доплера, видимое изменение частоты волны, излучаемой источником, движущимся относительно наблюдателя.
В этой модели самолет летит над наблюдателем. Желтые кружки представляют пики звуковых волн, излучаемых самолетом.


### Управляющие параметры:
- **PLANE-SPEED** определеяет какая будет скорость самолета
- **SHOW-AMPLITUDES**  переключатель позволяет увидеть силу звуковой волны на каждом участке воздуха.

### Внутренние параметры:
- **numeratort** проход каждого расчета слева-направо и сверху-вниз
- **column-number**. определяет количество строк

### Критерии эффективности системы:
- Практический подтверждение Эффект Доплера 

### Недостатки модели:
Движется только самолет

<br>

## Вычислительные эксперименты
<br>
### 2. Проведем  эксперимент, когда самолет не будет двигаться, но будет издавать звук
Установим ползунок PLANE-SPEED на 0 миль/час
<br>
![Рисунок 1](рис1.png)
С левой и правой стороны от самолета волны одинаково распостраняются во все стороны.
<br> Это нам и подтверждает график  ампилтуды

### 2. Проведем  эксперимент, когда самолет будет двигаться со скоростью МЕНЬШЕ, чем скорость звуковой волны
Установим ползунок PLANE-SPEED на 500 миль/час
<br>
![Рисунок 1](рис1.png)
<br>
Когда самолет двигается со скоростью меньше, чем скорость звуковой волны. Видим, что волны идущие к человеку справа, короче, чем те, которые идут слева. Это и есть эффект Доплера
![Рисунок 1](рис1.png)
<br>
График

### 2. Проведем эксперимент с конченой и бексонечной десятичной дробью
![Рисунок 4](рис4.png)
![Рисунок 5](рис5.png)

Некоторые шаблоны останавливаются после нескольких цифр, а другие повторяются вечно

### 3. Возможно ли получить изображение шахматной доски?

Чтобы результатом была шахматная доская период дроби должен состоять из двух чисел, а его целая часть соответствовать второй цифре в периоде.
<br>Допустим, 0,505050(50)
<br>Попробуем получить эту дробь:
<br>0,50(50) = Х
<br>50,50(50) = 100Х
<br>50=99Х
<br>Х=50/99
<br>Проверим результат:

![Рисунок 6](рис6.png)
![Рисунок 7](рис7.png)

<br>Первая цифра необязательно должна быть нулем:
<br>1,(01)=Х
<br><br><br>101.(01)=100х
<br><br>100=99х
<br>х=100/99

![Рисунок 8](рис8.png)

### 3. Возможно ли получить вертикальные полосы?
Отрегулировав полузнок width на четное число, всегда будут получатся вертикальный полосы: 

![Рисунок 9](рис9.png)

Получить вертикальные полосы на нечетном полузнке невозможно.

### 4. Как дробь будет приближена к числу Pi?
При условиях максимального знаменателя и числителя равному 100. Ближе всех будет дробь 22/7.

![Рисунок 9](рис10.png)

Модель показывает, что практический расчет соответствовует отоброжаемому результату
