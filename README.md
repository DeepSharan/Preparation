# Preparation



#include<iostream>
#include<climits>
using namespace std;
void in()
{
  int n;
  int i;
  cin>>n;
  
  int array[n];
  
  for(i = 0; i < n; i++)
  {
    cin>>array[i];
  }
  
  for(i = 0; i < n; i++)
  {
    cout<<array[i]<<"\t";
  }
}
                     
int maxmin()
{
  int n;
  int i;
  cin>>n;
  int arry[n];
  
  for(i = 0; i < n; i++)
  {
    cin>>arry[i];
  }
  
  int maxNo = INT_MIN;
  int minNo = INT_MAX;
  
  for(i = 0; i < n; i++)
  {
    if(arry[i] > maxNo)
    {
      maxNo = arry[i];
    }
    if(arry[i] < minNo)
    {
      minNo = arry[i];                  
    }                  
  }
  cout<<maxNo<<"\t"<<minNo<<"\n";
                 
  return 0;                   
                     
}
                             
int linearsearch(int arr[], int n, int key)
{
  for(int i = 0; i < n; i++)
  {
    if(arr[i] = key)
    {
      return i;
    }
  }
  return -1;                  
}                             

void linearuse()
{
  int n;
  cin>>n;
  
  int arr[n];
  for(int i = 0; i < n; i++)
  {
    cin>>arr[i];       
  }             
  
  int key;
  cin>>key;
  
  cout<<linearsearch(arr, n, key)
}











