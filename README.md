#include <iostream>
using std::string;

void repo()
{
   string name;
   std::cout << "What is your name";
   std::cin >> name;
   std::cout << "You welcome to my first repo " << name;
}
int main()
{
    repo();
return 0;
}
