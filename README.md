#include "iostream"

using namespace std;
  
int main()
{ 
  
  double n,jumlah;  

  double eth[10],rata; 
  
 cin>>n; 
  
 for(int i=0;i<n;i++){ 
   
 cin >> eth[i]; 
 } 
  
 jumlah=0; 
  
 for(int i=0;i<n;i++){ 
   jumlah = jumlah + eth[i]; 
    
 } 
    cout <<endl; 
    rata = jumlah/n; 
    
 cout<<"rata-rata   : " << rata; 
 cout<<" ETH"; 
 cout <<endl; 
 cout<<"total ETH   : " << jumlah; 
 cout<<" ETH"; 
 cout <<endl; 
 cout<<"dalam USD   :$" <<jumlah*4000; 
  
} 
