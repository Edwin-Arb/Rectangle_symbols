# Rectangle_symbols
Создание прямоугольника с помощью символов

#include<iostream>
using namespace std;

void main()
{
	setlocale(LC_ALL, "ru");

	int a, b;
	char sybol;

	cout << "Введите ширину прямоугольника: " << endl;
	cin >> a;

	cout << "Введите длину прямоугольника: " << endl;
	cin >> b;

	cout << "Введите символ:" << endl;
	cin >> sybol;

	cout << endl;

	for (int i = 0; i < a; i++)
	{
		for (int i = 0; i < b; i++)
		{
			cout << sybol;
		}
		cout << endl;
	}
}
