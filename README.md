//# templeate
//template c++

#include <iostream>
using namespace std;

template<class S>S add(S a=4, S b=5)
{
    S result=a+b;
    return result;
}
template<class S>S add(S a, S b, S c, S d)
{
 S result=a+b+c+d;
 return result ;
}

int main()
{
    int a=2;
    int b=3;
    int c=4;
    int d=6;
    cout<<add(a , b);
    cout<<add(c,a);
    cout<<add(c,d);
}
