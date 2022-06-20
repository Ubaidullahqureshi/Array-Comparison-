#include<iostream>
using namespace std;
	int main()
	{
		int num1 [ 5 ] , num2 [ 5 ] , i , equals = 0;
		
		// Input of 5 Integers of first Array
		cout << "Please Enter Five Integrs for the First Array " << '\n';
		for ( i = 0; i < 5; i++ ){
			cin >> num1 [ i ];
		}
		
	
		
		// Input of 5 Integers of Second Array
		cout << "Please Enter Five Integrs for the Second Array " << '\n';
		for ( i = 0; i < 5; i++ ){
			cin >> num2 [ i ];
		}
		
		// Display the Elements of two arrays 
		cout << "\n The Values in First Array are ";
		for ( i = 0; i < 5; i++ ){
			cout << "\t" << num1 [ i ];
		}
		
		cout << "\n The Values in Second Array are ";
		for ( i = 0; i < 5; i++ ){
			cout << "\t" << num2 [ i ];
		}
		
		// Compare Two Arrays 
		for ( i = 0 ; i < 5; i++ ){
			if ( num1 [ i ] != num2 [ i ] ){
				cout << "\n The Array are not Equal ";
				equals = 0;
				break;
			}
			equals = 1;
		} 
		if ( equals )
			cout << "\n Both Arrays are Equals";
	}
