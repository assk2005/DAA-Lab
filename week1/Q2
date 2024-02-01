#include <iostream>
using namespace std;

int main()
{
    int tc,inputs,bs,comp;
    int i,j,s,e,flag=0;
    cin>>tc;
    for(i=0;i<tc;i++)
    {
        flag=0;
        comp=0;
        cin>>inputs;
        int a[inputs];
        for(j=0;j<inputs;j++)
            cin>>a[j];
        cin>>bs;
        s=0;
        e=inputs-1;
        while(s<=e)
        {
        	comp++;
            j=(s+e)/2;
            if(bs==a[j])
            {
                flag=1;
                cout<<"Present "<<comp<<endl;;
                break;
            }
            else if(bs<a[j])
                e=j-1;
            else
                s=j+1;
        }
        if(flag==0)
            cout<<"Not Present "<<comp<<endl;
    }
    return 0;
}
