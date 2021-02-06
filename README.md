#include <iostream>
using namespace std;
int main()
{
	
	int i, j;
	int k = 0;
	int B[5][5], A[5][5] = { {1,2,3,7,9},{-5,-7,-8,4,5},{-3,-4,-5,-6,-7},{2,7,-6,8,-9},{4,11,-22,21,4} };
	for (i = 0; i < 5; i++);
	for (j = 0; j < 5; j++);
	setlocale(0, "ukr");
	for (int i = 0; i < 5; i++)
		for (int j = 0; j < 5; j++)
		{
			cout << A[i][j] << '\t';
			if (A[i][j] > 1 && A[i][j] < 10)k++;
		}
	cout << "\nКiлькiсть елементiв з (1; 10) рiвна " << k << "\n\n"; k = 0;
	for (int i = 0; i < 5; i++)
		for (int j = 0; j < 5; j++)
		{
			cout << A[i][j] << '\t';
			if (A[i][j] > 11 && A[i][j] < 25)k++;
		}
	cout << "\nКiлькiсть елементiв з (11; 25) рiвна " << k << "\n\n"; k = 0;
	for (int i = 0; i < 5; i++)
		for (int j = 0; j < 5; j++)
		{
			cout << A[i][j] << '\t';
			if (A[i][j] > 1 && A[i][j] < 10)k++;
		}
	cout << "\nКiлькiсть елементiв з (1; 20) рiвна " << k << "\n\n"; k = 0;

	
	cout << "Масив B:" << endl;
	for (int i = 0; i < 5; i++)
		for (int j = 0; j < 5; j++)
			
		{
			A[i][j] *= -1;
			cout << A[i][j] << " ";
		}
	
}
