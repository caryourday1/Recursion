# Recursion
#include<iostream>
using namespace std;

int factorialR(int n);

int main()
{
    int n;

    cout << " Enter number 4 ";
    cin >> n;

    cout << "FactorialR of " << n << " = " << factorialR(n);

    return 0;
}

int factorialR(int n)
{
    if(n > 1)
        return n * factorialR(n - 1);
    else
        return 1;
}
