#include<iostream>
#include<cmath>
using namespace std;

int main()
{
    int sqrtResult = sqrt(25); float ceil2Result;
    int ceilResult = ceil(4.2);
    int floorResult = floor(4.2);
    int powResult = pow(2, 3);
    int log2Result = log2(512);
    cout << sqrtResult << endl;
    cout << log2Result << endl;
    cout << ceilResult << endl;
    cout << floorResult << endl;
    
    cout <<"Please enter a floating point number which you want to round of up to an integer value" << endl;
    cin >> ceil2Result;
    ceil2Result = sqrt(ceil2Result);
    cout << ceil2Result << endl;
    return 0;
}
