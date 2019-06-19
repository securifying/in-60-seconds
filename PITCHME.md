# All about the Explicit Keyword
---
```c++
#include <iostream> 

using namespace std; 

class Complex 
{ 
private: 
	double real; 
	double imag; 

public: 
	// Default constructor 
	Complex(double r = 0.0, double i = 0.0) : real(r), imag(i) {} 

	// A method to compare two Complex numbers 
	bool operator == (Complex rhs) { 
	return (real == rhs.real && imag == rhs.imag)? true : false; 
	} 
}; 

int main() 
{ 
	// a Complex object 
	Complex com1(3.0, 0.0); 

	if (com1 == 3.0) 
	cout << "Same"; 
	else
	cout << "Not Same"; 
	return 0; 
} 
 

```
@[13] (What is this?)
@[16-18] (Inheriting from runtime_error class)
@[9-25] (Inheriting from runtime_error class)
@[26] (Interesting..?)
@[54] (See that parameter there?)
