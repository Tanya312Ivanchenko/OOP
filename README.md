OOP
===
#include <cstdlib>
#include <iostream>
using namespace std;
class IZDELIE
{
      protected:
  char* name;
  char* shifr;
  int kilkist;
      public:
        IZDELIE();
        IZDELIE(char*,char*, int)
        IZDELIE     
 ~IZDELIE();
           char* get_name();
           void set_name(double new_name);
           double get_shifr();
           void set_shifr(double new_shifr);
           double get_kilkist();
           void set_kilkist(double new_kilkist);
           void show();
           double abs();
}
IZDELIE::IZDELIE();
                 {
                        name=book;
                        shifr=0312;
                        kilkist=100;
                  cout<<"konstructor bez paramitrov"<<endl;
                 }
IZDELIE::IZDELIE(char* NAME, char*SHIFR, int KYLKIST);
                 {
                  this -> name=NAME;
                  this -> shifr=SHIFR;
                  this -> kilkist=KYLKIST;
                  cout<<"konstructor z paramitrov"<<endl;
                 }
izdelie::~izdelie();
{
                    cout"destructor"<<endl;
}

 void izdelie::show();
                     {
                     cout<<"("<<x<<","<<y<<","<<z<<")"
                     }
 //main.cpp
 //#include <vector.h>//??? ? ""
 main()
 {
       izdelie();
       izdelie(_imy,_shifr,_kolichestvo);
       izdelie.show();
  izdelie *p=new_izdelie;// что это?
  p ->show();
  deleta p();
  system("PAUSE");
  return 0;
}
