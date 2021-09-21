cout << "Storage room of code";
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
#include <iostream>
#include <string>
using namespace std;

int main ()
{
  string mystr;
  cout << "State your name and section ";
  getline (cin, mystr);
  cout << "Profile " << mystr << ".\n" << "has been saved.";
  cout << " ";
  cout << "Welcome " << mystr << ".\n" << "Class will begin shortly.";
  return 0;
}

\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
 
  #include <iostream>
using namespace std;

int main ()
{
  unsigned long n;
  do {
    cout << "Enter daily budget: ";
    cin >> n;
    cout << "You entered: " << n << " peso  (0 to end transaction)" << "\n";
  } while (n != 0);
  return 0;
}
 
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
  
  #include <iostream>
#include <string>
int main()
{ 
  std::string name;
  std::cout << "Username? ";
  getline (std::cin, name);
  std::cout << "Hello,I am " << name << "!\n"; 
  std::cout << "address? ";
  ;getline (std::cin, name);
  std::cout << "I live at " << name << "!\n"; 
 }
