//Zander Rammage's Fight for your life Gold+ Edition
#include <cstdlib>
#include <ctime>
#include <iostream>
#include <string>
#include <iomanip>
#include <stdlib.h>
using namespace std;

int me;
int tryagain;
string user;
int main ()
{
Start:
	system("cls");

	cout << "Please enter your name: ";
	cin >> user;

ANStart:
	system("cls");

	//declare and initialize integer and string arrays with values
	int gold[10] = {53, 49, 88, 48, 66, 76, 63, 76, 13, 71};
	string name[10] = {"0. Able", "1. Alvy", "2. Else", "3. Gale", "4. Gwen", "5. Gina", "6. Erik", "7. Milo", "8. Myrl", "9. Lena"};
	string name2[10] = {"Able", "Alvy", "Else", "Gale", "Gwen", "Gina", "Erik", "Milo", "Myrl", "Lena"};
	int defence [10] = {80, 110, 90, 90, 80, 100, 70, 90, 80, 90};
	string type [10] = {"Warlock", "Paladin", "Warrior", "Templar", "Healer", "Mystic", "Theif", "Scout", "Pirate", "Archer"};
	int attack [10] = {10, 7, 9, 9, 10, 8, 11, 9, 10 ,9};
	int counter = 0;

		//random number generator
	unsigned seed, randomNum;
	int pick;
	seed = ((unsigned int) time (0));
	srand(seed);
	randomNum = rand() % 9;
	pick =(int)randomNum;

	//display list of names and their respective gold
	cout << "   Name\t Type\tDefence\tAttack\tGold\n";
	cout << "--------------------------------------------\n";
	for (counter=0; counter<10; counter++)
	{ 
		cout << name[counter] << "\t";
		cout << type[counter] << "\t";
		cout << defence[counter] << "\t";
		cout << attack[counter] << "\t";
		cout << gold[counter] << "\t";
		cout << " \n";
	}

	cout << "\n";

	cout << "Welcome " << user << ".\n";

	cout << "Choose a character (0-9): ";
	cin >> me;

	system("cls");

	if (name[me] == name[pick])
	{
		cout << "I'm sorry, but you cannot pick the same person as the computer. Please pick someone else.";
		goto ANStart;
	}

	else
	{
		cout << "You are " << name2[me] << "\n";
		cout << "Your opponent is " << name2[pick] << "\n";
		system("pause");

		if (1)
		{
			//Fight to the death
			system("cls");
			cout << "Now,";
			_sleep(75);
			system("cls");
			cout << "Now, for";
			_sleep(75);
			system("cls");
			cout << "Now, for a";
			_sleep(75);
			system("cls");
			cout << "Now, for a fight";
			_sleep(75);
			system("cls");
			cout << "Now, for a fight to";
			_sleep(75);
			system("cls");
			cout << "Now, for a fight to the";
			_sleep(75);
			system("cls");
			cout << "Now, for a fight to the death";
			_sleep(750);
			system("cls");
			cout << "Now, for a fight to the death.";
			_sleep(750);
			system("cls");
			cout << "Now, for a fight to the death..";
			_sleep(750);
			system("cls");
			cout << "Now, for a fight to the death...\n";
			_sleep(750);
			system("cls");
		}

		//----------------------Attack and Defence------------------------
		while (defence[me] > 0 && defence[pick] > 0)
		{
			int Attack1, Attack2, Defence1, Defence2; //choose random numbers based on each players strength
			
			Attack1=1+rand()%attack[me];
			Attack2=1+rand()%attack[pick];
			Defence1=1+rand()%defence[me];
			Defence2=1+rand()%defence[pick];
	
					//------------------------First Players Turn!--------------------------
						//Display Your Person, The Random Person, and their respective status
			cout << name2[me] << "\t\t\t\t\t\t\t\t   " << name2[pick] << "\n";
			cout << type[me] << "\t\t\t\t\t\t\t\t   " << type[pick] << "\n";
			cout << "Defence: " << defence[me] << "\t\t\t\t\t\t\t   Defence: " << defence[pick] << "\n";
			cout << "Attack: " << attack[me] << "\t\t\t\t\t\t\t   Attack: " << attack[pick] << "\n";
			cout << "Gold: " << gold[me] << "\t\t\t\t\t\t\t   Gold: " << gold[pick] << "\n";
			cout << "-------------------------------------------------------------------------------\n";
			
			cout <<"  "<< name2[me] << "'s turn!\n  " << name2[me] << " Strikes with a Attack of " << Attack1 << "\n";
			cout <<"  "<< name2[pick] << " trys to block with a Defence of " << Defence2 << "\n  ";
			system("pause");
			system("cls");
	
			if (Attack1>Defence2)
			{
				defence[pick] = defence[pick] - attack[me];
	
							//Display Your Person, The Random Person, and their respective status
				cout << name2[me] << "\t\t\t\t\t\t\t\t   " << name2[pick] << "\n";
				cout << type[me] << "\t\t\t\t\t\t\t\t   " << type[pick] << "\n";
				cout << "Defence: " << defence[me] << "\t\t\t\t\t\t\t   Defence: " << defence[pick] << "\n";
				cout << "Attack: " << attack[me] << "\t\t\t\t\t\t\t   Attack: " << attack[pick] << "\n";
				cout << "Gold: " << gold[me] << "\t\t\t\t\t\t\t   Gold: " << gold[pick] << "\n";
				cout << "-------------------------------------------------------------------------------\n";
				
				cout << "  " << name2[pick] << " lost " << attack[me] << " Health!\n  ";
	
				system("pause");
				system("cls");
			}
	
			else if (Attack1<Defence2)
			{
				defence[me] = defence[me] - attack[pick];
	
							//Display Your Person, The Random Person, and their respective status
				cout << name2[me] << "\t\t\t\t\t\t\t\t   " << name2[pick] << "\n";
				cout << type[me] << "\t\t\t\t\t\t\t\t   " << type[pick] << "\n";
				cout << "Defence: " << defence[me] << "\t\t\t\t\t\t\t   Defence: " << defence[pick] << "\n";
				cout << "Attack: " << attack[me] << "\t\t\t\t\t\t\t   Attack: " << attack[pick] << "\n";
				cout << "Gold: " << gold[me] << "\t\t\t\t\t\t\t   Gold: " << gold[pick] << "\n";
				cout << "-------------------------------------------------------------------------------\n";
	
				cout << "  " << name2[me] << " lost " << attack [pick] << " Health!\n  ";
				
				system("pause");
				system("cls");
			}
	
			else
			{
							//Display Your Person, The Random Person, and their respective status
				cout << name2[me] << "\t\t\t\t\t\t\t\t   " << name2[pick] << "\n";
				cout << type[me] << "\t\t\t\t\t\t\t\t   " << type[pick] << "\n";
				cout << "Defence: " << defence[me] << "\t\t\t\t\t\t\t   Defence: " << defence[pick] << "\n";
				cout << "Attack: " << attack[me] << "\t\t\t\t\t\t\t   Attack: " << attack[pick] << "\n";
				cout << "Gold: " << gold[me] << "\t\t\t\t\t\t\t   Gold: " << gold[pick] << "\n";
				cout << "-------------------------------------------------------------------------------\n";
	
				cout << "  " << "Attack Dodged!\n  ";
				system("pause");
				system("cls");
			}
	
					//----------------------------Second Players Turn!--------------------------------
					//Display Your Person, The Random Person, and their respective status
			cout << name2[me] << "\t\t\t\t\t\t\t\t   " << name2[pick] << "\n";
			cout << type[me] << "\t\t\t\t\t\t\t\t   " << type[pick] << "\n";
			cout << "Defence: " << defence[me] << "\t\t\t\t\t\t\t   Defence: " << defence[pick] << "\n";
			cout << "Attack: " << attack[me] << "\t\t\t\t\t\t\t   Attack: " << attack[pick] << "\n";
			cout << "Gold: " << gold[me] << "\t\t\t\t\t\t\t   Gold: " << gold[pick] << "\n";
			cout << "-------------------------------------------------------------------------------\n";
	
			cout << "  " << name2[pick] << "'s turn!\n  " << name2[pick] << " Strikes with a Attack of " << Attack2 << "\n";
			cout << "  " << name2[me] << " trys to block with a Defence of " << Defence1 << "\n  ";
			
			system("pause");
			system("cls");
			
			if (Attack2>Defence1)
			{
				defence[me] = defence[me] - attack[pick];
	
							//Display Your Person, The Random Person, and their respective status
				cout << name2[me] << "\t\t\t\t\t\t\t\t   " << name2[pick] << "\n";
				cout << type[me] << "\t\t\t\t\t\t\t\t   " << type[pick] << "\n";
				cout << "Defence: " << defence[me] << "\t\t\t\t\t\t\t   Defence: " << defence[pick] << "\n";
				cout << "Attack: " << attack[me] << "\t\t\t\t\t\t\t   Attack: " << attack[pick] << "\n";
				cout << "Gold: " << gold[me] << "\t\t\t\t\t\t\t   Gold: " << gold[pick] << "\n";
				cout << "-------------------------------------------------------------------------------\n";
	
				cout << "  " << name2[me] << " lost " << attack[pick] << " Health!\n  ";
				
				system("pause");
				system("cls");
			}
	
			else if (Attack2<Defence1)
			{
				defence[pick] = defence[pick] - attack[me];
	
							//Display Your Person, The Random Person, and their respective status
				cout << name2[me] << "\t\t\t\t\t\t\t\t   " << name2[pick] << "\n";
				cout << type[me] << "\t\t\t\t\t\t\t\t   " << type[pick] << "\n";
				cout << "Defence: " << defence[me] << "\t\t\t\t\t\t\t   Defence: " << defence[pick] << "\n";
				cout << "Attack: " << attack[me] << "\t\t\t\t\t\t\t   Attack: " << attack[pick] << "\n";
				cout << "Gold: " << gold[me] << "\t\t\t\t\t\t\t   Gold: " << gold[pick] << "\n";
				cout << "-------------------------------------------------------------------------------\n";
	
				cout << "  " << name2[pick] << " lost " << attack [me] << " Health!\n  ";
				
				system("pause");
				system("cls");
			}
	
			else
			{
							//Display Your Person, The Random Person, and their respective status
				cout << name2[me] << "\t\t\t\t\t\t\t\t   " << name2[pick] << "\n";
				cout << type[me] << "\t\t\t\t\t\t\t\t   " << type[pick] << "\n";
				cout << "Defence: " << defence[me] << "\t\t\t\t\t\t\t   Defence: " << defence[pick] << "\n";
				cout << "Attack: " << attack[me] << "\t\t\t\t\t\t\t   Attack: " << attack[pick] << "\n";
				cout << "Gold: " << gold[me] << "\t\t\t\t\t\t\t   Gold: " << gold[pick] << "\n";
				cout << "-------------------------------------------------------------------------------\n";
	
				cout << "  " << "Attack Dodged!\n  ";
				system("pause");
				system("cls");
			}
		}
		//--------------------Win/Lose---------------------
		if (defence[me] <= 0)
		{
			cout << name[me] << " died! ";	
		}
	
		else if (defence[pick] < 0)
		{
			cout << name[pick] << " died! ";
	
			cout << "Congratulations, You won!\n";
		}
		cout << "Would you like to play again?\n";
		cin >> tryagain;
	
		if (tryagain == 1)
		{
			goto ANStart;
		}
	
		else
		{
			goto End;
		}
	
End:
		system("cls");
		cout << "Good bye, " << user << "!";
	} 
}
