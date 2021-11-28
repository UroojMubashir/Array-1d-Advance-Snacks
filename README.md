#include <iostream>
#include <array>
using namespace std;

int main()
{
   
array<string,4>arr = {"Mars Bar", "Snickers", "Bounty", "Wispa"};

cout << arr.at(1) << endl;//returns value at index 1 e.g. snickers cout << arr[¹] << endl; //does the same as the above
cout << arr[1]<< endl;

cout << arr.front() << endl;//returns value at beginning of array (Ma Bar)

cout << arr.back() << endl;//returns value at end of array (Wispa)

// utilise a for loop to run through array

for(int i = 0; i < arr.size(); i++){ //note use size() in condition

cout << arr.at(i) << ",";

}

cout << endl;
    return 0;
}

            
