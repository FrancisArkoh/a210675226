# a210675226
assignment 2
#include<iostream>
using namespace std;
int main(){
	int a;
	string b;
	cout<<"GRADING SYSTEM \n";
	cout<<"_______________\n\n";
	cout<<"Enter Your Grade: \n";
	cin>>a;
	if (a>=80)cout<<"A--Exellent";
	else if (a>=75)cout<<"B--Very Good";
	else if (a>=65)cout<<"c--Good";
	else if (a>=55)cout<<"D--Pass";
	else if (a>=45)cout<<"E--Weak";
	else cout<<"F--Fail";
	return 0;
}
