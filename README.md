# REVERSE-OF-ARRAY-IIN-C++
#include <iostream>
using namespace std;
int main()
{
    int num,arr[100],temp,i,j;
    cout<<" enter the size of array "<<endl;
    cin>>num;
    for(int i=0;i<num;i++){
        cout<<" enter the element"<<i+1<<" ";
        cin>>arr[i];
    }
    for(int i=0;i<num/2;i++){
        temp=arr[i];
        arr[i]=arr[num-1-i];
        arr[num-1-i]=temp;
    
    }
    cout<<" reverse of element"<<endl;
    for(int i=0;i<num;i++){
        cout<<arr[i]<<" ";
    }

    return 0;
}


OUTPUT
![image](https://github.com/user-attachments/assets/466c9b1f-c6a8-4f39-86be-e7cbece43f37)
