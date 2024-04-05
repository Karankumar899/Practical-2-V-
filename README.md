# Practical-2-V-
#include <iostream>
using namespace std;
int a = 24;

int main() {
    
    int a = 32;
    
    cout << "Local variable x: " << a << endl;

    cout << "Global variable x: " << ::a << endl;

    return 0;
}
