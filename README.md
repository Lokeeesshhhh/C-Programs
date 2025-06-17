# The-newspaper-Agency
#include<iostream>
using namespace std;
int main()
{
    int w,x,y,s;
    cout<<"Enter the no of copies of sold :";
    cin >>w;
    cout<<"Enter the cost per copy :"<<endl;
    cin>>x;
    cout<<"Enter the cost to agency of each newspaper :"<<endl;
    cin>>y;
    s=(w*x)-(w*y)-100;
    cout<<s<<endl;
    return 0;
}
