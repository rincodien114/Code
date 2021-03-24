#include <iostream>
using namespace std;
class hcn {
private:
  float d, r, dt, cv;

public:
  void nhap(float d, float r);
  void tinhdt(float d, float r);
  void tinhcv(float d, float r);
  void xuat();
};
void hcn::nhap(float d, float r){
//   cout<<"Nhap CD va CR: ";
//   cin>>d>>r;
}
void hcn::tinhdt(float d, float r){
	dt=d*r; 
}
void hcn::tinhcv(float d, float r){
	cv=(d + r)*2;
}
void hcn::xuat(){
  cout<<"Dien tich HCN= "<<dt<< endl;
  cout<<"Chu vi HCN= "<<cv<< endl;
}
int main(){
  hcn hinh[10];
  for (int i = 0; i < 10; i++) {
    cout<<"HCN"<<i+1<<"  ";
    hinh[i].nhap(4,5);
    hinh[i].tinhdt(4,5);
    hinh[i].tinhcv(4,5);
    hinh[i].xuat();
  }
}
