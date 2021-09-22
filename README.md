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
  
  #include <cstdlib>
#include <cstring>
#include <iostream>

using namespace std;

int main () {
    char monthName[10];
    short month, day, year;
    
    cout << "Enter month: ";
    cin >> month;
    
    cout << "Enter day: ";
    cin >> day;
    
    cout << "Enter year: ";
    cin >> year;
    cout << endl;
    
    switch (month) {
        case 1: strcpy(monthName, "January"); break;
        case 2: strcpy(monthName, "February"); break;
        case 3: strcpy(monthName, "March"); break;
        case 4: strcpy(monthName, "April"); break;
        case 5: strcpy(monthName, "May"); break;
        case 6: strcpy(monthName, "June"); break;
        case 7: strcpy(monthName, "July"); break; 
        case 8: strcpy(monthName, "August"); break;
        case 9: strcpy(monthName, "September"); break;
        case 10: strcpy(monthName, "October"); break;
        case 11: strcpy(monthName, "November"); break;
        case 12: strcpy(monthName, "December"); break;
        default: cout << "Invalid Month!" << endl;
}        
              
     if (!strcmp(monthName,"")) {{
         cout << monthName << " " << day << "," << year << endl;
         
}              
              
// ************************ DO NOT CHANGE **********************************
// Print a new line and ask user for any key before exiting
// *************************************************************************
cout << endl;
system("PAUSE");
return EXIT_SUCCESS

;}}
     
     
     
     
     
     
     
     
              
  
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
//////////////////////////////////////////////////////////////////////////////////////
  
 #include <iostream>
#include <string>

using namespace std;

int main() {
    char n;
    float num1, num2;
    cout << "Enter year number (1, 2, 3, 4, 5)";
    cin >> n;
    cout << "No. of units" << endl;
    cin >> num2;

    switch (n) {
        case '1':
            cout << num1 << " + " << num2 << " = " << num1 * num2;
            break;
        case '2':
            cout << num1 << " - " << num2 << " = " << num1 * num2;
            break;
        case '3':
            cout << num1 << " * " << num2 << " = " << num1 * num2;
            break;
        case '4':
            cout << num1 << " / " << num2 << " = " << num1 * num2;
            break;
        case '5':
            cout << num1 << " / " << num2 << " = " << num1 * num2;
            break;
        default:
         
            cout << "Error! The operator is not correct";
            break;
    }

    return 0;
}
