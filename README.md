# MyDreadWorld
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
#include <iostream>
using namespace std;
int main(){
    int lovelife=69;
    if(lovelife==0){
        cout<<"Aaah Kawawa"<<endl;
    }
    else if(lovelife==69){
        cout<<"Waw";
    }
    else{
        cout<<"Nice";
    }
    return 0;
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
