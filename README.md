#include<iostream>
using namespace std;
int main()
{
	int i = 0, fact =1 , num;
	cout << "Enter a number " << endl;
	cin >> num;
	while (num > 1)
	{
		fact = fact * num;
		num--;
	}
	cout << "The factorial of a number is :" << fact << endl;

}
