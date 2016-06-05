# quadratic-equation-solver
#include "std_lib_facilities.h"


int main()
{
	double a = 0;
	double b = 0;
	double c = 0;
	double D = 0;
	double y = 2;

	double x1 = 0;
	double x2 = 0;
	{


		cout << "write a number for a ";
		cin >> a;
		cout << "write a number for b ";
		cin >> b;
		cout << "write a number for c ";
		cin >> c;
		

		D = pow(b, 2) - (4 * a * c);

		cout << "D equals " << D << "\n";

		if (D <= -1)
		  
		{
			cout << "no solution\n";
		}
			
		else if (D == 0)

		{
			x1 = (-b + sqrt(D)) / (2 * a);

			cout << "1 solution\n" << "x equals " << x1 << "\n";
		}

		else

		{
			x1 = (-b + sqrt(D)) / (2 * a);
			x2 = (-b - sqrt(D)) / (2 * a);
			cout << "2 solutions\n" << "x1 equals " << x1 << "\n" << "x2 equals " << x2 << "\n";
		}
		
		keep_window_open();

	}
}


quadratic equation
