# githubinitial
#include <iostream>
using namespace std;
int pattern(int n)
{
    for(int i=0;i<n;i++)
    {
        for(int j=n-i;j>0;j--)
    
        {
          cout <<j;
        }
          cout<<endl;
    }
    return 0;
}
int main()
{
    int n;
    cout <<"n: ";
    cin >>n;
    
for(int i=0;i<n;i++)
{
    
    for(int a=n-i;a>0;a--)

        {
            pattern(a);
        }
    
}
}
