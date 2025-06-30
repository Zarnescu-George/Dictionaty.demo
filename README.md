# Dictionary.demo



#include <iostream>
#include <fstream>
using namespace std;
ifstream f("lista.in");
int x,v,i;
int main()
{
    cout<<"For english : 1";
    cout<<endl;
    cout<<"For spanish : 2";
    cout<<endl;
    cout<<"For german : 3";
    cout<<endl;
    cout<<"For russian : 4";
    cout<<endl;
    cout<<"For japanese : 5";
    cout<<endl;
    cout<<endl;
    cout<<"To stop press -1";
    cin>>x;
    if(x>5)cout<<"ERROR :)";
    if(x==1)
    {
        cout<<"choose a number from 1 to 10";
        cout<<endl;
        cin>>v;
        switch(v)
        {
        case 1 : cout<<"one";
            break;
        case 2 : cout<<"two";
            break;
        case 3:
            cout << "three";
            break;
        case 4:
            cout << "four";
            break;
        case 5:
            cout << "five";
            break;
        case 6:
            cout << "six";
            break;
        case 7:
            cout << "seven";
            break;
        case 8:
            cout << "eight";
            break;
        case 9:
            cout << "nine";
            break;
        case 10:
            cout << "ten";
            break;
        default : cout<<"none";
        }
    }
    if(x==2)
    {
        cout<<"elige un número del 1 al 10";
        cout<<endl;
        cin>>v;
        switch(v) {
        case 1: cout << "uno"; break;
        case 2: cout << "dos"; break;
        case 3: cout << "tres"; break;
        case 4: cout << "cuatro"; break;
        case 5: cout << "cinco"; break;
        case 6: cout << "seis"; break;
        case 7: cout << "siete"; break;
        case 8: cout << "ocho"; break;
        case 9: cout << "nueve"; break;
        case 10: cout << "diez"; break;
        default : cout<<"ninguno";
          }
    }
    if(x==3)
    {
        cout<<"wählen Sie eine Zahl zwischen 1 und 10";
        cout<<endl;
        cin>>v;
        switch(v) {
        case 1: cout << "eins"; break;
        case 2: cout << "zwei"; break;
        case 3: cout << "drei"; break;
        case 4: cout << "vier"; break;
        case 5: cout << "fünf"; break;
        case 6: cout << "sechs"; break;
        case 7: cout << "sieben"; break;
        case 8: cout << "acht"; break;
        case 9: cout << "neun"; break;
        case 10: cout << "zehn"; break;
        default : cout<<"keiner";
    }
    }
    if(x==4)
    {
        cout<<"выберите число от 1 до 10";
        cout<<endl;
        cin>>v;
        switch(v){
        case 1: cout << "один (odin)"; break;
        case 2: cout << "два (dva)"; break;
        case 3: cout << "три (tri)"; break;
        case 4: cout << "четыре (chetyre)"; break;
        case 5: cout << "пять (pyat')"; break;
        case 6: cout << "шесть (shest')"; break;
        case 7: cout << "семь (sem')"; break;
        case 8: cout << "восемь (vosem')"; break;
        case 9: cout << "девять (devyat')"; break;
        case 10: cout << "десять (desyat')"; break;
        default : cout<<"никто(nikto)";
        }
    }
    if(x==5)
    {
        cout<<"For vocal press 0 and for signs press 1";
        cin>>i;
        if(i==0)
        {
            cout<<"1 Kara 10 made no sūji o sentaku shite kudasai";
            cout<<endl;
            cin>>v;
            switch(v) {
        case 1: cout << "ichi"; break;
        case 2: cout << "ni"; break;
        case 3: cout << "san"; break;
        case 4: cout << "shi / yon"; break;
        case 5: cout << "go"; break;
        case 6: cout << "roku"; break;
        case 7: cout << "shichi / nana"; break;
        case 8: cout << "hachi"; break;
        case 9: cout << "kyū"; break;
        case 10: cout << "jū"; break;
        default : cout<<"nashi";
    }
        }
        else
            {
             cout<<"1から10までの数字を選択してください";
             cout<<endl;
             cin>>v;
             switch(v) {
        case 1: cout << "一"; break;
        case 2: cout << "二"; break;
        case 3: cout << "三"; break;
        case 4: cout << "四"; break;
        case 5: cout << "五"; break;
        case 6: cout << "六"; break;
        case 7: cout << "七"; break;
        case 8: cout << "八"; break;
        case 9: cout << "九"; break;
        case 10: cout << "十"; break;
        default : cout<<"なし";
    }
            }
    }
    if(x==-1)return 0;
    return 0;
}
