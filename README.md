#include <iostream>

using namespace std;

int main()
{
    bool isSyntax = false;
double num1;
double num2;
string op;

cout << "Welcome to the C++ Calculator developed by codemyster\n";
cout << "Enter your 1st number:";
cin >> num1;
cout << "Enter The Opperator:";
cin >> op;
cout << "Enter 2nd number:";
cin >> num2;
double done;
if(op == "+" || op == "addition"){
    done = num1 + num2;
}else if(op == "-" || op == "subtraction"){
done = num1 - num2;
}else if (op == "*" ||op == "multipulcation"){
done = num1 * num2;
}else if(op == "/" || op == "division"){
done = num1 / num2;
}else{
    isSyntax = true;
cout << "Invalid Syntax";
}
if(!isSyntax){
    cout << "Your awnser is " << done << "!";
}

}
