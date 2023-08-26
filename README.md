#include<iostream>
using namespace std;
int main()
{
    double hours, pay, Salary;
    string currency;
    cout<<"How many Hours did you work?\n";
    cin >> hours;
    cout<<"What was your pay for each hour?\n";
    cin >> pay;
    cout<< "Currency?\n";
    cin >> currency;
    Salary = pay * hours;
    cout <<"Your Salary is= " << Salary << currency;
    return 0;
}
