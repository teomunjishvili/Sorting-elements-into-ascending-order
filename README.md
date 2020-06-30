#include<iostream>
#include<algorithm>
using namespace std;
int main()
{
    int Numbers[10];
    for(int i=0; i<10; i++)
    {
        cout<<"Please enter the values: "<<endl;
        cin>>Numbers[i];
    }
    
    cout<<"The ascending order is:"<<endl;
    sort (begin(Numbers), end(Numbers));
    for(auto x: Numbers)
        cout<<x<<endl;

    
    return 0;
}
