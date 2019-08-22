#MyDreadWorld
ƒaded
1.
int main(){
    int x=10000000;
        while(true){
        printf("%i",x);
        x+=1500;
    }    
    return 0;
}


2.
#include <stdio.h>

int main(){
    
    char c= 'A';
    
    
    
    
    return 0;
} 

3.
#include <iostream>
using namespace std;
int main(){
    char c='c';
    cout <<c<<endl;
} 
A to Z alphabetically


4. Data Type = Identifier = Value

#include <iostream>
using namespace std;
int main(){
    int x = 10;
    long y = 1000000;
    double dd = 100.0;
    float ff = 100.0f;
    char xx = 'f';
    bool bb = true;
    string cooked = "love";
    cout <<x<< endl;
    cout <<y<< endl;
    cout <<dd<< endl;
    cout <<ff<< endl;
    cout <<xx<< endl;

    return 0;
}    



5. If-else
#include <iostream>
using namespace std;
int main(){
    int lovelife=99;
    if(lovelife==0){
        cout<<"Aaah Kawawa"<<endl;
    }
    return 0;
}

6. Else if and else


}

7. Else if and else part 2
#include <iostream>
using namespace std;
int main(){
    int lovelife=2;
    if(lovelife==0){
        cout<<"Aaah Kawawa"<<endl;
    }
    else if(lovelife==69){
        cout<<"Waw";
    }
    else if(lovelife==04){
        cout<<"Nice";
    }
    else if(lovelife==01){
        cout<<"Hello po";
    }
    else{
        cout<<"Ayaw Ku";
    }
    return 0;
}


4. LOOPS
#include <iostream>

using namespace std;

int main()
{
    //While loop -- sentinel-controlled
    int x = 0;
    while(x != 99){
        cout<<"Enter a number:";
        cin >> x;
    }
    cout<<"Loop ended"<<endl;
    return 0;
}


5. With WHILE LOOP
#include <iostream>

using namespace std;

int main()
{
    //While loop -- sentinel-controlled
    int x = 0;
    while(x != 99){
        cout<<"Enter a number:";
        cin >> x;
    }
    cout<<"Loop ended"<<endl;
    
6. COUNTER CONTROLLED LOOP
#include <iostream>
using namespace std;
int main()
{
    //Counter-based loop
    
    for(int x = 2;x<=20;x+=2)
        cout<<x<<endl;
    return 0;
}    
AND
#include <iostream>
using namespace std;
int main()
{
    //Counter-based loop
    
    for(int x = 1;x<20;x++)
        cout<<x<<endl;
    return 0;
}
    
    //do-while
    int y = 0;
    do{
       cout<<"Enter a number:";
       cin >> y;
    }while(y != 99);
    cout<<"Do-while loop ended."<<endl;
    return 0;
}

7.OPERATORS
100 - 150 PROBLEM
ANSWER IN MATHEMATICAL     
150>= x >= 100   
151> x > 99
 
IN PROGRAMMING
X>=100&&X<=150
X>99&&<151

8.
 
#include <iostream>

using namespace std;
int main()
{   
    //variable declaration
    int pangalawa69 = 100;
    float bebeko = 99.5f;
    float bebeka = 99.0f;
    double hahaha = 60.0;
    bool abc = true;
    bool cde = false;
    bool def = bebeko > bebeka;
    bool fgh = def && true;
    cout << abc << endl;
    cout << cde << endl;
    cout << fgh << endl;
    cout << bebeko << endl;
    cout << bebeka << endl;
    cout << pangalawa69 << endl;
    cout<<"Hello World"<<endl;
    
    // Arithmertic Operators
    int addition = 10 + 10; // +
    cout << addition << endl;
    int subraction = 10 - 10;// -   
    cout << subraction << endl;
    int division = 25 / 5; // /
    cout << division << endl;
    int multiplication = 5 * 5;
    cout << multiplication << endl;
    int module = 17 % 35;
    cout << module << endl;
    
    //Logical Operators
    
    //AND
    
    cout << " AND" << endl;
    
    bool  bebebex = true && true;
    bool aa = true && false;
    bool bb = false && true;
    bool cc = false && false;
    
    cout << bebebex << endl;
    cout << aa << endl;
    cout << bb << endl;
    cout << cc << endl;
    
    //OR 
    
    cout << " OR" << endl;
    bool dd = true || true;
    bool ee = true || false;
    bool ff = false|| true;
    bool gg = false || false;
    
    cout << dd << endl;
    cout << ee << endl;
    cout << ff << endl;
    cout << gg << endl;
    
    // COMPARISON
    cout << " COMPARISON" << endl;
    bool gt = 50 > 39;
    bool lt = 69 <70;
    bool gtoreq = 50 >= 49;
    bool ltoreq = 70 <= 70;
    bool eq = 50 == 50;
    bool noteq = 99 !=20;
    
    cout << gt << endl;
    cout << lt << endl;
    cout << gtoreq << endl;
    cout << ltoreq << endl;
    cout << eq << endl;
    cout << noteq << endl;
    
    // Conditionals
     int baon = 999;
     if (baon >=200){ //200 up 
        cout << " Papasok" << endl;
    }    
    else if(baon >= 100){
        cout << " Papasok pero magkacuting" << endl;
    }
    else{
        cout << " Tambay" << endl;
    }   
    
    int Months = 13;
    switch (Months){
        case 1:
            cout<<"January01"<<endl;
            break;
        case 2:
            cout<<"February02"<<endl;
            break;
        case 3:
            cout<<"March03"<<endl;
            break;
        case 4:
            cout<<"April04"<<endl;
            break;
        case 5:
            cout<<"May05"<<endl;
            break;
        case 6:
            cout<<"June06"<<endl;
            break;
        case 7:
            cout<<"July07"<<endl;
            break;
        case 8:     
            cout<<"August08"<<endl;
            break;
        case 9:
            cout<<"September09"<<endl;
            break;
        case 10:
            cout<<"October10"<<endl;
            break;
        case 11:
            cout<<"November11"<<endl;
            break;
        case 12:
            cout<<"December12"<< endl;
        default: cout<<"Undefined ENGOT!"<<endl;
    }
    return 0;
}
