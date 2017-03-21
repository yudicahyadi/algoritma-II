#include<stdio.h>
#include <iostream>
using namespace std;
int main()
{
   int n, x = 0, a = 1, y, ulang,sum;
 
   cout<<"input no = ";
   cin>>n;
 
   cout<<"angka fibonacchi = " << n <<endl;
 
   for ( ulang = 0 ; ulang < n ; ulang++ )
   {
      if ( ulang <= 1 )
         y = ulang;
      else
      {
         y = x + a;
         x = a;
         a = y;
      }
      cout<<y<<endl;
      sum = sum + y;
   }
    cout << "Total : " << sum << endl;
   return 0;
}
