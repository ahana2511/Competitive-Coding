#include<bits/stdc++.h>
using namespace std;
#define ll unsigned long long int 
int main(){
    ll q;
    cin>>q;
    while(q--){
        ll n;
        cin>>n;
        ll a[n],x=0;
        for(int i=0;i<n;i++){
            cin>>a[i];
        }
        if(n%2==0)
        x=0;
        else{
            for(int i=0;i<n;i+=2)
            x=x^a[i];
        }
        cout<<x<<endl; 
    }
    return 0;
}
