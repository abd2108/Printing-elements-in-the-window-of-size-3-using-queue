#include <iostream>
#include<queue>
#include<algorithm> 
#include<vector> 
#include<stack>  
#include<__tree> 
#include<grp.h>
using namespace std; 
#define  longlong ll; 
void display(queue<int>q){
    while(!q.empty()){
        cout<<q.front() ;
        q.pop(); }
}
int main() { 
    queue<int>q ; 
    int n ; 
    cin>>n ; 
    int arr[n] ; 
    for(int i=0;i<n;i++){
        cin>>arr[i];
    } int k=3 ; 
    for(int i=0;i<k-1;i++){
q.push(arr[i]);
    } 
    for(int i=k-1;i<n;i++){
q.push(arr[i]) ; 
display(q) ; cout<<endl;
q.pop();
    } 
    
}
      
  
