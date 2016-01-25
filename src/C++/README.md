#HugeInt Class#


A C++ class implementation of big integer. This is a beta version.


Example
---------



    
    #include <iostream>
	#include "hugeInt.h"
	using namespace std;

	int main()
	{
		string s1("93869465387524561257334594937043965783853863");
		string s2("4987034978348567346598349583405349083475387623243284692368545302");
		
		hugeInt n1(s1);
		hugeInt n2(s2);
		
		hugeInt n3 = n1 * n2;
		hugeInt n4 = n3.pow(10);

		cout << "Length of n3 is " << n3.len() << endl << endl;
		cout << n4 << endl << endl;
		return 0;
	} // end main

Note
------

	The hugeInt class was written as a pet project and is lacking in some areas
	feel free to test, modify and improve the class.
	

License
----------
    Copyright (c) 2015 Mbadiwe Nnaemeka Ronald ron2tele@gmail.com

    This software is provided 'as-is', without any express or implied
    warranty. In no event will the author be held liable for any damages
    arising from the use of this software.
    Permission is granted to anyone to use this software for any purpose,
    including commercial applications, and to alter it and redistribute it
    freely, subject to the following restrictions:
    
    1. The origin of this software must not be misrepresented; you must not
    claim that you wrote the original software. If you use this software
    in a product, an acknowledgment in the product documentation must be
    specified.
    
    2. Altered source versions must be plainly marked as such, and must not be
    misrepresented as being the original software.
    
    3. This notice may not be removed or altered from any source distribution.
        
        