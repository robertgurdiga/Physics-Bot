#include <iostream>
#include <cmath>
#include <stdlib.h>
using namespace std;
int main(){
    int m,speed,miu,vox,G,F,a,i,ii,l,angle,deltal;
    string v;
    cout<<"Cate valori se dau?"<<endl;
    cin>>i;
    cout<<"Cate valori se intreaba?"<<endl;
    cin>>ii;
    cout<<"Let the magic begin!"<<endl;
    system("cls");
        cout<<"Se da"<<endl;
    while(i){
    cin>>v;
    if(v=="m"){
         cin>>m;
         cout<<"m = "<<m<<" Kg"<<endl;
    }
    else if(v=="l" or v=="lo"){
        cout<<"l = ";
        cin>>l;
        cout<<" m"<<endl;
    }
    else if(v=="deltal"){
        cout<<"delta l = ";
        cin>>deltal;
        cout<<" m"<<endl;
    }
    else if(v=="alpha"){
        cout<<"alpha = ";
        cin>>angle;
        cout<<" degrees"<<endl;
    }
    else if(v=="v" or v=="vx"){
        cout<<"v = ";
        cin>>speed;
        cout<<" m/s"<<endl;
    }
    else if(v=="vox"){
        cout<<"vox = ";
        cin>>vox;
        cout<<" km/s"<<endl;
    }
    else if(v=="miu"){
        cout<<"miu = ";
        cin>>miu;
    }
    else if(v=="a"){
        cout<<"a = ";
        cin>>a;
        cout<<" m/s^2"<<endl;
    }
    else if(v=="F"){
                    cin>>F;
        cout<<" = "<<" N"<<endl;
    }
    else if(v=="G"){
        cout<<"G = ";
        cin>>G;
        cout<<" N"<<endl;
    }
            i--;
}
while(ii){
        cin>>v;
        if(v=="m"){
        cout<<"m = ?"<<endl;
    }
    else if(v=="v" or v=="vx"){
        cout<<"v = ?"<<endl;
    }
    else if(v=="vox"){
        cout<<"vox = ?"<<endl;
    }
    else if(v=="miu"){
        cout<<"miu = ?"<<endl;
    }
    else if(v=="a"){
        cout<<"a = ?"<<endl;
    }
    else if(v=="F"){
        cout<<"F = ?"<<endl;
    }
    else if(v=="G"){
        cout<<"G = ?"<<endl;
    }
    else if(v=="k"){
        cout<<"k = ?"<<endl;
    }
    else if(v=="v"){
        cout<<"v = ?"<<endl;
    }
    ii--;
}
    cout<<"Cunosc"<<endl;
    if(a!=0 && m!=0)
        F=a*m;
        cout<<"F=a*m"<<endl;
        cout<<"Calcul Matematic"<<endl;
        cout<<"F ="<<a<<" m/s^2"<<"*"<<m<<" kg"<<"="<<a*m<<" N"<<endl;
        cout<<"Raspuns: F="<<F<<" N";
}

