# Assessment-code-
#include<string.h>
#include<iostream.h>
#include<conio.h>
class Emp
{
      int empid;
      char empname[20];
      float sal;
      public:
      void getemp( int id, char name[20], float basic);
      void putemp( );
};
void emp::getemp( int id, char name[20], float basic)
{
       empid=id;
       strcpy(empname)=name;
       sal=basic;
}
void emp::putemp( )
{
     cout<<"empid="<<empid<<endl;
     cout<<"empname="<<empname<<endl;
     cout<<"empsalary="<<sal;
}
void main( )
{
    emp e;
    clrscr( );
    e.getemp(101, PRAJNA, 10000);
    e.putemp( );
    getch( );
}
