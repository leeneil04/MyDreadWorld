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



9. POKEMON APProgram

#include<iostream>
#include<string>

using namespace std;
//Global variables
string POKEMON_1 = "Pikachu";
string POKEMON_2 = "Tachi";

//Pokemon Hp
int hp1 = 60;
int hp2 = 65;

//Function Prototypes
void displayHPBar(int);

int main(){
    displayHPBar(hp1);
    return 0; 
}

//Function Definitions

void displayHPBar(int hp){

    for(int x=hp;x>0;x-=5) {
        cout<< "|";
    }  
    cout << endl;
}
 10. POKEMON 
#include<iostream>
#include<string>

using namespace std;
//Global variables
string POKEMON_1 = "Pikachu";
string POKEMON_2 = "Tachi";

//Pokemon Hp
int hp1 = 60;
int hp2 = 65;

//Function Prototypes
void displayHPBar(int);
void displayPikachuSkills();
void displayTachiSkills();

int main(){
    
    cout<<POKEMON_1<<":";
    displayHPBar(hp1);
    cout<<POKEMON_2<<":";
    displayHPBar(hp2);
    
    displayPikachuSkills();
    
    int choice;
    cout<<"Enter skill number:";
    cin>>choice;
    
    switch(choice){
        case 1:
            cout<<"Pikachu used Thunder Volt!";
            hp1 -= 10;
            break;
           case 2:
            cout<<"Paralyze Measure Influence!";
            hp1 -= 10;
            break;
            case 3:
            cout<<"Regen Volt Immune!";
            hp1 -= 10;
            break;
            case 4:
            cout<<"Sleeping Kit Activated!";
            hp1 -= 10;
            break;
            default:
                cout<<"Please Enter Proper Skill Number."<<endl;
    }        
    return 0; 
}

void displayPikachuSkills(){
    
        string PikachuSkills[] = {"Thunder Volt","Paralyze Measure","Regen Volt","Sleeping Kit"};
        int length = sizeof(PikachuSkills) / sizeof(PikachuSkills[0]);
        
        for(int x=0;x<length;x++){
            cout<<x+1<<"."<<PikachuSkills[x]<<endl;
        }
}
void displayTachiSkills(){
    
        string TachiSkills[] = {"Fist Pucnch","Unstappable Kick","Regen Aura","Ultimate Flay"};
        int length = sizeof(TachiSkills) / sizeof(TachiSkills[0]);
        
        for(int x=0;x<length;x++){
            cout<<x+1<<"."<<TachiSkills[x]<<endl;
        }
}       
//Function Definitions

void displayHPBar(int hp){

    for(int x=hp;x>0;x-=5) {
        cout<< "|";
    }  
    cout <<hp<< endl;
}

11. POKEMON WITH VICTORY QUOTE
#include<iostream>
#include<string.h>
#include<cstdlib>

using namespace std;
//Global variables
string POKEMON_1 = "squirtle";
string POKEMON_2 = "pikachu";

int hp1 = 60;
int hp2 = 65;


//Function Prototypes
void displayHPBar(int);
void displaySquirtleSkills();
void displayPikachuSkills();

void retaliate();

int main(){
    
    while(hp1 > 0 && hp2 > 0){
        cout<<POKEMON_1<<":";
        displayHPBar(hp1);
        cout<<POKEMON_2<<":";
        displayHPBar(hp2);
        
        displaySquirtleSkills();
        
        int choice;
        cout<<"enter skill number:";
        cin>>choice;
        
        switch(choice){
            case 1:
             cout<<"squirtle used tackle"<<endl;
             hp1 -=10;
             break;
            case 2:
             cout<<"squirtle used tail whip"<<endl;
             hp1 -= 10;
             break;
            case 3:
             cout<<"squirtle used bite"<<endl;
             hp1 -= 10;
             break;
            case 4:
             cout<<"squirtle used bubble beam!"<<endl;
             hp1 -= 10;
             break;
            default: cout<<"Enter correct number!"<<endl;
        }
        
        retaliate();
    }
    
    if(hp1 <= 0){
        cout<<"Squirtle fainted!"<<endl;
    }
    else{
        cout<<"Pikachu fainted!"<<endl;
    }
    
    return 0;
}

void displaySquirtleSkills(){
    string SquirtleSkills[] = {"Tackle","Tail Whip","Bite","Bubble Beam"};
    int length = sizeof(SquirtleSkills) / sizeof (SquirtleSkills[0]);
    
    for(int x=0;x<length;x++){
        cout<<x+1<<"."<<SquirtleSkills[x]<<endl;
    }
}

//Function Definitions


void displayHPBar(int hp){
    for(int x=hp;x>0;x-=5){
        cout << "|";
    }
    cout <<hp<<endl;
}

void retaliate(){
    int randSkil = rand() % 4 + 1;
    
    switch(randSkil){
        case 1:
         cout<<"Pikachu used tackle!"<<endl;
         hp2 -=10;
         break;
        case 2:
         cout<<"Pikachu used iron tail!"<<endl;
         hp2 -= 10;
         break;
        case 3:
         cout<<"Pikachu used thunder!"<<endl;
         hp2 -= 10;
         break;
        case 4:
         cout<<"Pikachu used spark!"<<endl;
         hp2 -= 10;
         break;
        default: cout<<"Enter correct number!"<<endl;
    }
}


12.ROMAN NUMERALS

#include<iostream>

using namespace std;

void convertRoman(int num);

int main()
{ 
    int num=999;
   convertRoman(num);
    return 0;
    
}
    
void convertRoman(int num){   
    if(num>=1000){
        cout<<"M";
        convertRoman(num-1000);
    }
    else if(num>=500){
        cout<<"D";
        convertRoman(num-500);
    }
    else if(num>=100){
        cout<<"C";
        convertRoman(num-100);
    }
    else if(num>=50){
        cout<<"L";
        convertRoman(num-50);
    }
    else if(num>=10){
        cout<<"X";
        convertRoman(num-10);
    }
    else if(num>=9){
        cout<<"IX";
        convertRoman(num-9);
    }
    else if(num>=5){
        cout<<"v";
        convertRoman(num-5);
    }
    else if(num>=1){
        cout<<"I";
        convertRoman(num-1);
    }
    
}

13.CALCULATOR
#include <iostream>
using namespace std;
int main()
{
    cout << "Lee Neil's Calculator" << endl;
    char op;
    float num1, num2;
    cout << "Enter operator + or - or * or /: "; cin >> op;
    cout << "Enter 1st number: "; 
    cin >> num1; 
    cout << "Enter 2nd number: "; 
    cin >> num2; 
    
    switch(op)
    {
        case '+':
            cout<<"Answer for Addition is ("<<num1<<"+"<<num2<<"): ";
            cout << num1+num2;
            break;
        case '-':
            cout<<"Answer for Suctraction is ("<<num1<<"-"<<num2<<"): ";
            break; 
        case '*':
            cout<<"Answer for Multiplication is ("<<num1<<"*"<<num2<<"): ";
            break;
        case '/':
            cout<<"Answer for Division is ("<<num1<<"/"<<num2<<"): ";
            break;
        default:
            // If the operator is other than +, -, * or /, error message is shown
            cout << "Error! operator is not correct";
            break;
    }
    return 0;
}
14, CALCULATOR WITH DO WHILE OR PA ULIT-ULIT
#include <iostream>
using namespace std;
int main()
{
    cout << "Lee Neil's Calculator" << endl;
    char op,redo;
    float num1, num2;
    
    do{
    cout << "Enter operator + or - or * or /: "; cin >> op;
    cout << "Enter 1st number: "; 
    cin >> num1; 
    cout << "Enter 2nd number: "; 
    cin >> num2; 
    

    switch(op)
    {
        case '+':
            cout<<"Answer for Addition is ("<<num1<<"+"<<num2<<"): ";
            cout << num1+num2 << endl;
            break;
        case '-':
            cout<<"Answer for Suctraction is ("<<num1<<"-"<<num2<<"): ";
            cout << num1-num2 << endl;
            break; 
        case '*':
            cout<<"Answer for Multiplication is ("<<num1<<"*"<<num2<<"): ";
            cout << num1*num2 << endl;
            break;
        case '/':
            cout<<"Answer for Division is ("<<num1<<"/"<<num2<<"): ";
            cout << num1/num2 << endl;
            break;
        default:
            // If the operator is other than +, -, * or /, error message is shown
            cout << "Error! operator is not correct"<<endl;
            break;
            
    }
        //----now once again the program will ask the user if want to continue or not
        cout<<"Please enter n or N to continue:";
        cin>>redo;
        cout<<endl<<endl;
    }
    while(redo=='n'||redo=='N');
    return 0;
}

15. Arrays
#include <iostream>
using namespace std;

int main(){
    int abc[]={1, 2, 3, 4};
    cout<<abc[0];
    
    return 0;
}

16.Table in c++
#include <iostream>

using namespace std;

int main(){
    
    for(int x = 2;x<8;x++){
        for(int y = 1;y<6;y++){
        cout<<(x * y)<<" ";
        }   
        cout<<endl;
    }
    return 0;
}    

17. Multiplication Table

#include <iostream>

using namespace std;

int main()
{
    for(int x = 1;x<11;x++){
        for(int y=1;y<11;y++){
            cout<<(x*y)<<" ";
        }
        cout<<endl;
    }
    return 0;
}

18. With even the Odds Number in Multiplication

#include <iostream>

using namespace std;

int main(){
    for(int x =1;x<11;x++){
        for(int y =1;y<11;y++){
            if((x*y)%2==1){
                cout<< "O" <<" ";
                }
                else{
                    cout<< x * y <<" ";
                }     
            } 
            cout<<endl;
        }
    return 0;
}

19. GGPYTHON ASS (Umar Javed)

#include<iostream>

using namespace std;

int main (){
    cout<< "Enter Your Age Here: ";
    int age;
    cin >>age;
    
    if(age==20){
        cout<< "Here's a wrisband" <<endl;
    }
    else if(age==19){
        cout<< "Here's a wristband" << endl;
    }
    else if(age==18){
        cout<<"Here's a wristband" << endl;
    }    
    else if(age<=17){
        cout<<"Please Leave" << endl;
    }
    else 
        cout<< "Welcome the user"<< endl;
    return 0;
}

20. produc of first number

#include <iostream>

using namespace std;

int main()
{
    
    int x;
    int y;

    cout<< "Enter First Number: ";
    cin >> x;
    cout <<"Enter Second Number: ";
    cin >> y;
    int z=x+y;
    cout <<z <<endl;
    
    if(z>x){
    cout << "Sum is greater";
    }
  
    return 0;
}

21. Using Esacape Sequence
#include <iostream>

using namespace std

//using escape sequence
int main()
{
    cout << "*****\n\tabc\n***\nabc\tedf\nsound" << endl;

    return 0;
}
