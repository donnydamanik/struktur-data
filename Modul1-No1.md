#include <iostream>
using namespace std;
int main(){
  int array[100], i, n;
  float rata, total=0;
  cout << "=================================" << endl;
  cout << "Ahmad Donny Damanik / 21091397008" << endl;
  cout << "================================= \n" << endl;
  cout << "Masukkan banyaknya data: ";
  cin >> n;
  for(i=0; i<n; i++){
    cout << "Data Ke-" << i+1 << " : ";
    cin >> array[i];
    total = total + array[i];
  }
  rata = total/n;
  cout << "Banyaknya data : " << n << endl;
  cout << "Rata-rata : " << rata << endl;
  cout << "Jumlah : " << total << endl;

  return 0;
}
