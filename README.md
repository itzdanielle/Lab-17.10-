# Lab-17.10-
#include <iostream>
using namespace std;

int math1() {
  int num1 = 50;
  int num2 = 5;
  return num1 + num2;
}

int math2() {
  int num1 = 50;
  int num2 = 5;
  return num1 - num2;
}

int multiplyer () {
  cout << "Enter 2 numbers\n";
  int num1, num2;
  cin >> num1 >> num2;
  return num1 * num2;
}

int main() {
  int outputNum;
  outputNum = multiplyer(); 
  cout << outputNum << endl;
}


// the output of this program is 45 since we know the numbers given and the output that the program will output is math2(). We know this because of the last main wants to only output math2().
