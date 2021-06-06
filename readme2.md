#include <iostream>
using namespace std;

int main()
{
  int num1, num2, i, num, digit, sum;

 

  cout << "Armstrong numbers between " << num1 << " and " << num2 << " are: " << endl;
  for(i = num1; i <= num2; i++)
  {
        sum = 0;
        num = i;

       
        {
            digit = num % 10;
            sum = sum + digit * digit * digit;
        }

        if(sum == i)
        {
            cout << i << endl;
        }
  }

  
}
