# P2Triangle.cpp
//Juan Pablo González Huezzo / A01224902
#include <iostream>
using namespace std;

	int triangle(int x){
		for(int a=1; a<=x; a++){
			for (int b=1; b<=a; b++){
				cout << "t";
			}
			cout << endl;
		}
		for(int c=x-1; c>=0; c--){
			for (int d=1; d<=c; d++){
				cout << "t";
			}
			cout << endl;
		}
	return 0;
	}

int main(){
	int n;
	cout << "What size do you want the triangle? " << endl;
	cin >> n;
	cout << endl;
return triangle(n);
}
