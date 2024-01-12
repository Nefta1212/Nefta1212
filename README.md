#include <iostream>
using namespace std;

int main (){
    int n1, n2;
    
    cin>> n1;
    cin >> n2;
    
    if(n1 > n2){
    cout<< "mayor" <<  endl;}
   else if(n1 < n2){
    cout<< "menor" <<  endl;}
    else if(n1 = n2){
    cout<< "igual" <<  endl;}
    
    return 0;
    
}
