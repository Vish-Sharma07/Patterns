# Patterns No Triangle Reverse
#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"Enter no of rows : ";
    cin>>n;
    for(int i=1; i<=n; i++){
        for(int j=i; j<=n-1; j++){
            cout<<" "<<" ";
        }
        for(int k=1; k<=i; k++){
            cout<<k<<" ";
        }
        cout<<endl;
    }
    
}
