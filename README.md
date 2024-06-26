## Самусевич Антон Георгиевич | 110901
*[Лабораторные работы](https://antonsamusevich.github.io/PIIS-EVT-labs.github.io/)*

### Контактная информация
1. **Email:** *AntonSamusevich03@gmail.com*
2. **GitHub:** *[AntonSamusevich](https://github.com/AntonSamusevich)*
3. **Телефон:** +375447886270

### Краткое описание
*Я целеустремленный и ответственный разработчик с опытом работы в веб-разработке и базах данных. Мои сильные стороны включают в себя умение быстро учиться, тщательное тестирование кода и эффективное решение проблем. Я заинтересован в поиске новых вызовов и развитии профессиональных навыков.*

### Навыки
![](icons/c.png) ![](icons/java.png) ![](icons/kotlin.png) ![](icons/python.png) ![](icons/mysql.png) ![](icons/js.png) ![](icons/html.png) ![](icons/css.png)
```
#include <iostream>
#include <iomanip>
#include <ctime>
using namespace std;

int main()
{
	srand(time(NULL));
	setlocale(LC_ALL, "RUS");

	int** arr = new int* [5]; //создание массива

	//генерация матрицы
	for (int i = 0; i < 5; i++)
	{
		arr[i] = new int[7]; //создание массива столбцов
	}
	for (int i = 0; i < 5; i++)
	{
		for (int j = 0; j < 7; j++)
		{
			arr[i][j] = rand() % 100;
		}
	}

	//просмотр матрицы
	cout << "Matrix" << endl;
	for (int i = 0; i < 5; i++)
	{
		cout << "|";
		for (int j = 0; j < 7; j++)
		{
			cout << setw(3) << arr[i][j] << setw(2);
		}
		cout << "|" << endl;
	}
	cout << endl;

	//освобождение памяти
	for (int i = 0; i < 5; i++)
	{
		delete[] arr[i];
	}
	delete[] arr;
}
```

### Опыт работы

> Работал над курсовым проектом по разработке консольного приложения на языке программирования C++ на тему «Расчет стажа работников предприятия».
> Занимался разработкой desktop-приложения «Программное средство для формирования меню ресторана» на языке Java, используя JavaFX и базу данных MySQL.
> Участвовал в разработке проекта «Контрольно-пропускная система предприятия», используя также JavaFX и MySQL.

### Образование

| Годы      | Образовательное учреждение                                             | Образование |
|-----------|------------------------------------------------------------------------|-------------|
| 2010-2021 | Средняя школа №151 г. Минска                                           | Среднее     |
| 2021-2025 | Белорусский государственный университет информатики и радиоэлектроники | Высшее      |

### Английский язык
~~A1 Beginner~~, ~~A2 Elementary~~, B1 Intermediate
