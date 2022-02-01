//Exception-Handling-in-c-
//Exception handling/ Error handling in c++ , condition when denominator is zero.
#include <iostream>

using namespace std;

int main()
{
    int a=10;
    int b=0;
    int divide;
    try{//it detach exception and throws peremeter
    if(b==0)
    throw": Division is not posible when b is zero :";// containing user friendly msg in one peremeter
    
    divide=a/b;
    }
    catch(const char*Ex)//it catch and handles(prents the exception) the exception which is sent by throw
  {
      cout<<Ex;
  }
   return 0;
}
