# First-Fast-Practice-Program-
It is about Hours of Work,Pay, Salary......

#include<iostream>
using namespace std;
int main()
{
    int hours, pay, Salary;
    string currency;
    cout<<"How many Hours did you work?";
    cin >> hours;
    cout<<"What was your pay for each hour?";
    cin >> pay >> currency;
    Salary = pay * hours;
    cout <<"Your Salary is= " << Salary << currency;
    return 0;
}
