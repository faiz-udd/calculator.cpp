# calculator.cpp
cout<<"Advanced Calculator using C++"
#include<iostream>
#include<cmath>
  using namespace std; 
  void addition()
  {          float x,y,z;     
  cout<<"Please Enter your Numbers: "<<endl;   
  cin>>x>>y;     z=x+y;  x=y; z+=y;  
  cout<<"sum of the numbers is: "<<z<<endl; 
  } 
  void subtraction(){     float x,y,z;     cout<<"Please Enter your Numbers: "<<endl;  
  cin>>x>>y;  
  z=x+y;  
  x=y;   
  z+=y;  
  cout<<"Subtraction of the numbers is: "<<z<<endl;   }  
  void division(){     float x,y,z;  
  cout<<"Please Enter your Numbers: "<<endl;   
  cin>>x>>y;     z=(float)x/(float)y; 
  cout<<" division of the Numbers is: "<<z<<endl; }
  void multiply(){     float x,y,z;   
  cout<<"Please Enter your Numbers: "<<endl;   
  cin>>x>>y; 
  
  z=x*y;   
  x=y;   
  z*=y;    
  cout<<" Multiplcation  of the Numbers is: "<<z<<endl; } 
  void squarert(){     double x;     cout<<"Please Enter the Number: "<<endl;  
  cin>>x;     double squareroot=sqrt(x);  
  cout<<"square root of the numbers is: "<<squareroot; }
  void cubert(){      double x;      cout<<"Please Enter the Number: "<<endl;     cin>>x;    double cuberoot=cbrt(x);     cout<<"cube root of the numbers is: "<<cuberoot; } 
  void sineval(){     double x;     cout<<"Please Enter the Number: "<<endl;     cin>>x;     double sinevalue=sin(x);     cout<<"sine value of the Number is: "<<sinevalue; }
  void cosineval(){     double x;     cout<<"Please Enter the Number: "<<endl;     cin>>x;     double cosinevalue=cos(x);     cout<<"cosine value of the Number is: "<<cosinevalue;  } 
  void tangentval(){     double x;     cout<<"Please Enter the Number: "<<endl;     cin>>x;     double tangentvalue=tan(x);     cout<<"tangent value of the Number is: "<<tangentvalue; }
  void square(){     double b;     cout<<"Please Enter the Number: "<<endl;     cin>>b;     double power=pow(b,2);     cout<<"square of the number is : "<<power;  } 
  void cube(){     double b;     cout<<"Please Enter the Number: "<<endl;     cin>>b; double cube=pow(b,3);     cout<<"cube of the number is : "<<cube;  }
  void power(){     double a,b;     cout<<"Please Enter the Base Number: "<<endl;     cin>>b;     cout<<"Please Enter the exponent Number: "<<endl;     cin>>a;          double power= pow(b,a);     cout<<"Power value of the Given base and power is: "<<power; } 
  int main() {     cout<<"1: Addition"<<endl;     cout<<"2: Subtraction"<<endl;     cout<<"3: Division"<<endl;     cout<<"4: Multiplication"<<endl;     cout<<"5: squareroot"<<endl;     cout<<"6: cuberoot"<<endl;     cout<<"7: sine"<<endl;     cout<<"8: cosine"<<endl;     cout<<"9: tangent"<<endl;     cout<<"10: square"<<endl;     cout<<"11: cube"<<endl;     cout<<"12: power of"<<endl;      int choice;    while(1){                cout<<"First Select the operator"<<endl;        cin>>choice;        switch(choice){        case 1:        addition();        break;         case 2:        subtraction();        break;         case 3:        division();        break;         case 4:        multiply();        break;         case 5:        squarert();        break;         case 6:        cubert();        break;         case 7:        sineval();        break;         case 8:        cosineval();        break;         case 9:        tangentval();        break;         case 10:        square();        break;         case 11:        cube();        break;         case 12:        power();        break;            }  } void addition(); void subtraction(); void division(); void multiply(); void squarert(); void cubert(); void sineval(); void cosineval(); void tangentval(); void square(); void cube(); void power(); return 0; }
