#include <iostream>
 using namespace std;
  
  int main()
{
  cout << "Aici doar introducand 3 date puteti afla volorile: Δ, X1, X2. Daca funcita de fradul II este de forma ''ax^2 + b + c'. Se accepta si numere negative" << endl; 
    int a;                                                  // pt functia ax^2 +/- bx +/0  c         
  cout << "Type a valute for a !" << endl;
cin >> a;
    int b;
  cout << "Type a valute for b !" << endl;
cin >> b;
    int d = b*b;                                            // ii b^2
    int c;
  cout << "Type valute for c !" << endl;
cin >> c;
    int x = d-(4*a*c);                                      // x ii delta 
  cout <<"Δ = "  << x << endl ;
    int unu = ( 0 - b + x ) / ( 2*a );                      // unu = X1
    int doi = ( 0 - b - x ) / ( 2*a );                      // doi = X2
  cout << "X1 = " << unu << endl;
  cout << "X2 = " << doi << endl;  
}  
