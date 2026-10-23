# program-to-calculate-the-average-of-dynamically-allocated-array-elements.

#include<iostream>
  using namespace std;
 int main(){
     int n;
     cout<<"enter size";
     cin>>n;

     int *p=new int[n];
     int sum =0;

     cout<<"enter "<<n<<"elements"<<"\n";
     for(int i=0;i<5;i++){
         cin>>p[i];
         sum=sum=+p[i];
     }

     float avg=float(sum)/n;
     cout<<"average :"<<avg;

     delete p;

     return 0;

 }
