 #include <iostream>
 using namespace std;

int main () {

   int x = 1;
 while(x >= 1 || x <= 4); { // Choose options between 1 & 4.

cout <<"Enter your choice or return the menu: " "\n";
cin >> x;

if ( x >= 4 ) {
cout <<"Program runs" <<endl;
} else if ( x <= 4 ) {
 cout <<"Program runs";
 } else {
 cout <<"Exit the Program";
}
     
cout <<"Your option: " << x <<"\n";
cout << "Invalid input. Try again: ";
cin.clear(); // Reset input errors
cin.ignore(10000, '\n'); // Remove bad input
}

int digit1;
int digit2;

int mycalc (int digit1, int digit2); {
    return digit1 + digit2;
    return digit1 - digit2;
    return digit1 * digit2;
}

 int value1;
 int value2;
cout <<mycalc(value1, value2) <<endl;

int exit = 4;
cout <<"To end the program press: " <<exit <<endl;

return 0;

}
  


 
