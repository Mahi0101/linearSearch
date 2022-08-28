# linearSearch
#include&lt;iostream> using namespace std; int linearSearch(int arr[],int key,int n){        for(int i=0;i&lt;=n;i++){ if(arr[i]==key){     return i; }     } return -1; } int main(){     int arr[]={1,2,4,6};     int key=4;  int n= sizeof(arr) / sizeof(arr[0]);     cout&lt;&lt;"element index is "&lt;&lt;linearSearch( arr,key,n)&lt;&lt;endl;     return 0; }
