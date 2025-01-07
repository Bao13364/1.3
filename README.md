# 1.3
#include <iostream>
#include<string>
using namespace std;
struct filmdata
   {
     string filmname;
 string director;
 string producer;
 int yeareleased;
   };
int main() {
   filmdata film1;
   cout<<"enter film name: "<<film1.filmname<<endl;   getline(cin,film1.filmname);

   cout<<"enter director: "<<film1.director<<endl;   getline (cin,film1.director);

   cout<<"enter producer: "<<film1.producer<<endl;   getline (cin,film1.producer);

   cout<<"enter released year: "<<film1.yeareleased<<endl;   
   cin>>film1.yeareleased;
   
   cout<<"film name : "<<film1.filmname<<endl;
cout<<"director :"<<film1.director<<endl;
cout<<"producer: "<<film1.producer<<endl;
cout<<"released year : "<<film1.yeareleased<<endl;
    return 0;
}
