#include<iostream>     
#include <math.h>      
using namespace std;

int main()
{ 
  double  t,a,r,x ;
	
  cout<<"nhap so tien ban dau  :";
  cin>>a;
	
  cout<<"lai suat(%) r :";
  cin>>r;
	
  cout<<"nhap so tien ki vong   :";
  cin>>t;
	
  x = (log(t/a)/log(1+r)); //logarit co so h cua g	
  cout<<"So nam de duoc so tien ky vong  la  :  "<<x<<endl ;	
	
  return 0;
}
