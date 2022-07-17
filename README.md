#include <iostream>
#include <cmath>
using namespace std;
int main()
{
	int pi = 3.14;
	int a;
	int b;
	int c;
	
	cout << "please enter A " << endl;
	cin >> a;

	cout << "please enter B " << endl;
	cin >> b;

	cout << "please enter C " << endl;
	cin >> c;

	
	int P = (a + b + c ) / 2;
	double T = (a * b * c) / (4 * sqrt(P * (P - a) * (P - b) * (P - c)));
	int T = T * T;
	int Area = pi * T;
	int AreaRound = round(Area);
	
	cout << "result " << Area << endl;
	cout << "Round " << AreaRound;
	return 0;
}
