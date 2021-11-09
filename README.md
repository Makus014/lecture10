# lecture10



//Descending Stars, Seven lines
  #include <iostream>
using namespace std;


int main() {

	for (int i = 1; i <= 7; i++) {
		for (int j = i; j <= 7; j++) {
			cout << "*";

		}
		cout << endl;
	}

	return 0;
  
  }
  
  
  
//Rising stars, Five lines
  #include <iostream>
using namespace std;


int main() {

	for (int i = 5; i >= 1; i--) {
		for (int j = i; j <= 5; j++) {
			cout << "*";

		}
		cout << endl;
	}

	return 0;
  }
                
                
 //Rising and Falling stars
  #include <iostream>
  using namespace std;

  int main() {

	for (int i = 5; i >= 1; i--) {
		for (int j = i; j <= 5; j++) {
			cout << "*";
		}
		cout << endl;
	}
	for (int i = 1; i <= 4; i++) {
		for (int j = i; j <= 4; j++) {
			cout << "*";

		}
		cout << endl;
	}

	return 0;
}

                
                
                
                
                
//cubes
 #include <iostream>
using namespace std;

int main() {

	for (int n = 0; n <= 5; n++) {
		if (n == 1) {
			cout << "Number is : 1 and the cube of 1 is: 1" << endl;
		}
		else if (n == 2) {
			cout << "Number is : 2 and the cube of 2 is : 8" << endl;
		}
		else if (n == 3) {
			cout << "Number is : 3 and the cube of 3 is: 27" << endl;
		}
		else if (n == 4) {
			cout << "Number is : 4 and the cube of 4 is: 64" << endl;
		}
		else if (n == 5) {
			cout << "Number is : 5 and the cube of 5 is: 125" << endl;
		}
	}


	return 0;
}   
                                                               
 // find the 9s
 #include <iostream>
using namespace std;


int main() {

	int total=0;

	for (int i = 100; i < 200; i++) {
		if (i % 9 == 0) {
			cout << i << endl;
			total = total + i;
		}
	}
	cout << total << endl;
	return 0;
}
