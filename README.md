# fibbonacci-series
It forms a sequence, called the Fibonacci sequence, such that each number is the sum of the two preceding ones, starting from 0 and 1. 
#include <isotream>
using namespace std;
int main()
{
  int x;
  cout<<"Enter number of terms";
  cin>>x;
  fib(x);
}
int fib(int n)
{
  if (n==0)
  {
    return 0;
  else if(n==1)
  {
    return 1;
  }
  else if
  {
    return fib(n-1) + fib(n-2);
  }
return 0;
}
