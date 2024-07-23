# linear-search-using-c-
you are given an integer array A of size n,sorted in non descending order.you are also given an integer 'target; .your task is to write a function to search for target in the array A .If it exist  return its index in zero base indexing using linear search in c++.

#include<iostream>

using namespace std;

int main()

{ 
 int n, A[10],target, flag=0,i;

cout<<"enter size of array";
cin>>n;
for(i=0;i<n;i++) 
{
cout<<"enter element";
cin>>A[i];
} 
cout<<"enter element for search";
cin>>target;
for(i=0;i<n;i++)
{ 
    if(target==A[i])
{
    flag=1;
    break;
}
}
if (flag==1)
{ 
    cout<<"element found at "<<i<<" position";
}
else
{
cout<<"not found";
}
}
