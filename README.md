# Lecture8-II---Cipherschools
This repository is about introduction of function

#include<iostream>
using namespace std;

/*void printstuff()  // there are no parameters
{
	cout<<"Writing my first function";
}

int main()
{
	printstuff();
	return 0;
}*/

int sum(int a,int b)
{
	int c;
	c=a+b;
	return c;
}
int main(){
	int a,b;
	int add_sum;
	a=3;
	b=5;
	add_sum = sum(a,b);
	cout<<add_sum;
	return 0;
}
