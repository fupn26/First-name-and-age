# First-name-and-age
#include "std_lib_facilities.h"
int main()
{
cout<<"PLease enter your first name and age\n";
string first_name;
int age;
cin>>first_name;
cin>>age;
cout<<"Hello, "<<first_name<<" (age "<<age<<")\n";
}

# With this little extension you can check how many month you are and you can enter a floatin-point number.
#include "std_lib_facilities.h"
int main()
{
cout<<"PLease enter your first name and age\n";
string first_name;
double age;
cin>>first_name;
cin>>age;
int month = age * 12;
cout<<"Hello, "<<first_name<<" (age: "<< age <<", month: "<<month<<")\n";
}
