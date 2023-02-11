//This is basic program of c++
#include<iostream> // Iostream is file where implementation of cout is place here
using namespace std; // So that we don't have to write std:: again and again
int main(){ // Similar to the start of flowchart 
    // std::cout<<"Namaste Bharat"; // Print on the screen
    cout<<"Namaste Bharat"; // Strings are enclosed inside double inverted commas
    cout<<2; // Inverted commas can be avoided incase of numbers
    cout<<"2"; // String 2 is printed
    cout<<'2'; // Character 2 is printer
}

//This program is for int,char

#include<iostream>
using namespace std;
int main(){
    int a = 5; // Integer data type  
    char ch = 'a'; // Character data type
    char ch1 = 256; // This gives us an error as 0-255 characters can be stored only and hence overflow occurs.
    return 0;
}


