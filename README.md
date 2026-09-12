#include<iostream>
using namespace std;
int main(){
    int days;
    cin >> days;

    int year = days / 365;
    int reaminderDays = days % 365;

    cout << year <<" years, " <<reaminderDays <<" days";
    return 0;


}
