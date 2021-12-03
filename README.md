# Array-art
#display art using array
#include<iostream>
using namespace std;
int main()
{
	string art[5][5] = { {"-----"},{"-0-0-"},{"-@@@-"},{"-^^^-"},{"-VVV-"}};
	for(int k=0; k<5; k++)   //using nested for loop 
		for (int z = 0; z < 5; z++)
		{
			cout <<"\n"<< art[k][z];
		}
	cout << endl;
	return 0;
}
