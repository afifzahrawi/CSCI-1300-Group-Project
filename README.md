#include <iostream>
using namespace std;

void create();
void remove();
void edit();
void search();
void appointment();

struct PatientData
{
	string name;
	int date;
	
}

int main ()
{
	int selection;
	cout << "Welcome to Hospital Registration! \n";
	
	
	
	while(selection < 6)
	{
		cin >> selection;
		
		
		if(selection == 1)
		{
			create();
			system("cls");
		}
		else if (selection == 2)
		{
			remove();
			system("cls");
		}
		else if (selection == 3)
		{
			edit();
			system("cls");
		}
		else if (selection == 4)
		{
			search();
			system("cls");
		}
		else
		appointment();
		system("cls");
	}
	
	return 0;
}

void create()
{
	cout << "pick 1";
}
void remove()
{
	cout << "pick 2";
}
void edit()
{
	cout << "pick 3";
}
void search()
{
	cout << "pick 4";
}
void appointment()
{
	cout << "pick 5";
}
