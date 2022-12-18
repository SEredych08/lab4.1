# lab4.1
// Lab_04_1.cpp
// < Середич Олег >
// Лабораторна робота № 4.1
// Цикли.
// Варіант 16

#include <iostream>
#include <cmath>
using namespace std;
int main()
{
	int  N ;
	double S ,j;
	cout << "N = "; cin >> N;
	S=0
	j = 2;
	while (j <= N)
	{
		S += (j * (N - j)) / (j * j * (N - j) * (N - j));
		j++;
	}
	cout << S << endl;
	S = 0;
	j = 2;
	do {
		S += (j * (N - j)) / (j * j * (N - j) * (N - j));
		j++;
	} while (j <= N);
	cout << S << endl;
	S = 0;
	for (j = 2; j <= N; j++)
	{
		S += (j * (N - j)) / (j * j * (N - j) * (N - j));
	}
	cout << S << endl;
	S = 0;
	for (j = N; j >= 2; j--)
	{
		S += (j * (N - j)) / (j * j * (N - j) * (N - j));
	}
	cout << S << endl;
	return 0;
 
