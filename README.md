# Prova_GIT
#include<iostream>


#include<string>
#include"Accum.h"
using namespace std;

int main() {
	Accum<int> integer(0);

	integer += 3.6;
	cout << integer.GetTotal() << endl;
	Accum<int> integer_1(10);

	//cout << integer_1(1).Accum() << endl; // come faccio a fare una chiamata diretta?

}
