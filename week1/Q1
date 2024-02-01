#include <iostream>
using namespace std;

int main()
{
    int tc,inputs,linear;
    int i,j,flag;
    cin>>tc;
    for(i=0;i<tc;i++)
    {
        flag=0;
        cin>>inputs;
        int a[inputs];
        for(j=0;j<inputs;j++)
            cin>>a[j];
        cin>>linear;
        for(j=0;j<inputs;j++)
        {
            if(linear==a[j])
            {
                flag=1;
                cout<<"Present "<<j+1<<endl;
                break;
            }
        }
        if(flag==0)
            cout<<"Not Present "<<inputs<<endl;
    }
    return 0;
}
