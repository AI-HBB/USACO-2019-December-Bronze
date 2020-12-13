#include <iostream>
#include <string>
using namespace std;
int main(){
//freopen("gymnastics.in", "r", stdin);
//freopen("gymnastics.out", "w", stdout);
int N,K,ar[10][20],a,b,a1=-1,b1=-1,ans,ansm=0;
cin >> K >> N;
for(int i=0; i<K; i++){
  for(int k=0; k<N; k++){
   cin >> ar[i][k];
}
}
  for(int k=0; k<N-1; k++){
   for(int j=k+1; j<N; j++){
     ans=1;
     a=ar[0][k];
     b=ar[0][j];
     for(int z=1; z<K; z++){
         
      for(int x=0; x<N; x++){
       if(a==ar[z][x]){
         a1=x;
       }
       if(b==ar[z][x]){
         b1=x;
       }
       }
       if(a1<b1){
        ans++;}
  }
  if(ans==K){
       ansm++;}
  }
  
  } 
  
cout << ansm;
}

