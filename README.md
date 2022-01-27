#include<iostream>
using namespace std;

int main() {
	int input;
	cout << " enter a month by its number" << endl;
	cin >> input;


	if (input == 1)
		cout << " January has 31 days " << endl;

	else if (input == 2)
		cout << " february has 28 days" << endl;

	else if (input == 3)
		cout << " March has 31 days" << endl;

	else if (input == 4)
		cout << " April has 30 days" << endl;

	else if (input == 5)
		cout << " May has 31 days" << endl;

	else if (input == 6)
		cout << " June has 30 days" << endl; 

	else if (input == 7)
		cout << " July has 31 days" << endl;

	else if (input == 8)
		cout << " August has 31 days" << endl;

	else if (input == 9)
		cout << " September has 30 days" << endl;

	else if (input == 10)
		cout << " October has 31 days" << endl;

	else if (input == 11)
		cout << " November has 30 days" << endl;

	else if (input == 12)
		cout << " December has 31 days" << endl;


	int room = 1;

	string input;
	do {

		switch (room) {
		case 1:



			cout << " You are in room 1, you can go up, left or 'r'ight" << endl;
			cin >> input;
			if (input == 'up')
				room = 2;
			else if (input == 'left')
				room = 3;
			else if (input == 'r')
				room = 4;

			else
				cout << " sorry not an option" << endl;

			break;


		case 2:



			cout << " You are in room 2, you can go down" << endl;
			cin >> input;
			if (input == 'down')
				room = 1;

			else
				cout << " sorry not an option" << endl;

			break;




		case 3:



			cout << " You are in room 3, you can go to the 'r'ight" << endl;
			cin >> input;
			if (input == 'r')
				room = 1;

			else
				cout << " sorry not an option" << endl;

			break;




		case 4:



			cout << " You are in room 4, you can go to the right" << endl;
			cin >> input;
			if (input == 'left')
				room = 1;
			else if (input == 'down')
				room = 5;


			else
				cout << " sorry not an option" << endl;

			break;



		case 5:



			cout << " You are in room 5, you can go up" << endl;
			cin >> input;
			if (input == 'up')
				room = 4;



			else
				cout << " sorry not an option" << endl;

			break;
		}
	} while (input != 'q');


}
