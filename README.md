Вводим с клавиатуры количество элементов в массиве строк;

Задаем массив строк в соответствии с введенным размером массива;

Заполняем массив через метод, принимающий исходный пустой массив:

  int i = 0;
  
  пока  i < длина массива,
  
   элемент массива вводится с клавиатуры, 
   
   i = i+1;
   
Выбираем элементы массива, соответствующие условию задачи через метод, принимющий заполненный массив:

int j = 0;

  пока  j < длина массива,
  
   элемент (строка) массива представляется как массив из символов,
   
   если длина этого массива <=3,
   
    этот массив выводится в консоль в виде строки;
    
   j = j+1.
  


