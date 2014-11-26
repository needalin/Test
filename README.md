Test (C++ Project)
======
Main .cpp file
------

'''
    
    // ConsoleApplication6.cpp Defines the entry point for the console application.
    
    #include <iostream> // IDE library directive does not need quotes
    #include "golf.h"
    using namespace std;

    int main()
    {
	compare get_values // 'weather' is the name of the class "aka world in lecture tutorial" 
    	value.get_values  // 'variable1' is the piece of the math function I want to run 
	value.temp(); // 'output' is the piece of the math function I want to run 
	value.members();
	
    	system("pause"); 
	return 0;
    }
    
'''

Header File
------

'''

     #include <iostream> // # sign indicates a direcive/macro
     using namespace std; 
    
    class compare
    {
    public:
        void get_values();
        void compare_values();
        void EvenOdd();
    private:
        int val1;
        int val2;
    };
    void compare::get_values()
    {
    std::cout << "Enter num1: "; //information goes out
        std::cin >> val1;
        std::cout << "Enter num2: "; // information goes in
        std::cin >> val2;
    }
    void compare::compare_values()
    {
        if (val1> val;

        std::string res = "even"; //set a default value
        if (val%2) res = "odd"; // a number is even if it is 0 modulo 2 and odd otherwise
        std::cout << "The value " << val << " is an " << res << " number\n";
    }
    void compare::EvenOdd()
    {
	int val = 0;
	std::cout << "testing for odd or even...";
	std::cout << "please enter an integer:";
	std::cin >> val;

	std::string res = "even"; //set a default value 
	if (val%2) res = "odd"; //a number is tested to check if it is TRUE or FALSE. 
	//% in C++ means "remainder" modulus
	//false = remainder 0; true = remainder 1
	//means: IF true, output "if" statement. IF  false, skip "if" statement

	//boolean data type: data type that holds either true or false (1 or 0)
	//comparison statement: evaluates a statement by comparison. 
	//2+2 == 4 evaluates to true 2+5 evaluates as false.

	std::cout << "the value" << val << "is an" << res<< "number\n";
        }
         system("pause");  
         return 0;
        }
    
'''
