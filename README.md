#include <iostream> 
#include <math.h> 
using namespace std; 
class Number {; 
public: 
 int N; 
 int K; 
 int result; 
 int result_1; 
 void res(){ 
  cout << "Школьников: "; 
   cin >> N; 
  cout << "Яблок: "; 
   cin >> K; 
   if(K>=N) 
   { 
  result = K/N; 
  cout <<"каждый получил: "<< result << endl; 
  result_1 = K % N; 
  cout <<"в корзине: "<< result_1 << endl; 
   } 
  else  
 
   cout <<"фигте"<< endl; 
    
 } 
}; 
int main() 
{ 
 setlocale(LC_ALL, "Russian"); 
 Number num; 
 num.res(); 
  
}
