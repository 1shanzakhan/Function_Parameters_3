# Function_Parameters_3
C++ Program

    #include <iostream>

    using namespace std;
    void myFunction(string fname, int age) {
      cout << fname << " LastName. " << age << " years old. \n";
    }

    int main() {
      myFunction("FirstName#1", 3);
      myFunction("FirstName#2", 14);
      myFunction("FirstName#3", 30);
      return 0;
    }
