Find and element in an array through Linear search.


#include<iostream>
using namespace std;
int main()
{
    int arr[20], i, num, index;
    cout<<"Enter Numbers: ";
    for(i=0; i<20; i++)
        cin>>arr[i];
    cout<<"\nEnter a Number to Search: ";
    cin>>num;
    for(i=0; i<20; i++)
    {
        if(arr[i]==num)
        {
            index = i;
            break;
        }
    }
    cout<<"\nFound at Index No."<<index;
    cout<<endl;
    return 0;
}
