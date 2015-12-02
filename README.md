TrueFit-challenge
This file contains the answers to the three TrueFit challenge questions.


//Challenge #1:
//This first program is written in C++
//The output should be something like:
//1: 1
//2: 2
//3: Fire
//4: 4
//etc

#include <iostream>

using namespace std;

int main()
{
	for (int i = 1; i <= 100; i++)
	{
		//Check to see if number is a multiple of both 3 and 7
		if (((i % 3) == 0) && ((i % 7) == 0))
		{
			cout << i << ": Fire and Ice" << endl;
		}

		//Otherwise check to see if number is a multiple of just 3
		else if ((i % 3) == 0)
		{
			cout << i << ": Fire" << endl;
		}

		//Otherwise check to see if number is a multiple of just 7
		else if ((i % 7) == 0)
		{
			cout << i << ": Ice" << endl;
		}

		//Otherwise, print the number
		else 
		{
			cout << i << ": " << i << endl;
		}
	}

	return 0;
}
