#include<iostream>
using namespace std;
int main()
{
    int n;
    cin>>n;
    
    int row=1;
    while(row<=n)
    {
        int num=1;
        
        while(num<=n-row+1)
        {
            cout<<num<<" ";
            num++;
        }
        
        int star=1;
        
        while(star<=2*(row-1))
        {
            cout<<"*"<<" ";
            star++;
        }
        
        num=n-row+1;
        
        while(num>=1)
        {
            cout<<num<<" ";
            num--;
        }
        
        cout<<endl;
        row++;
        
    }
}
