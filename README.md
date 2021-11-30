# cplus2.0_forloops
what num entered is how many times its printed

#include <iostream>
using namespace std;

int main()
{
    int grade;
     
    cout<<" Enter a number: \n";
    cin>> grade;
     
    for (int i=grade; i>=0; i--)
    {
        cout << "Practice more!\n ";
    }
    return 0;
}
  /*output:
  
  Enter a number: 
  3
  Practice more!
  Practice more!
  Practice more!
  Practice more!
  */
  
