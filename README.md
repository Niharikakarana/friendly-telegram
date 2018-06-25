//# friendly-telegram
//Geeksforgeeeks
//Maximum height of the staircase

#include <iostream>
using namespace std;

int main() {
    int test, i, sum, j, num;
    cin>>test;
    for(i=0; i<test; i++)
    {
        cin>>num;
        sum=0;
        for(j=1; j<num; j++)
        {
            sum+=j;
            if(sum>=num)
            break;
        }
        cout<<j;
    }
	//code
	return 0;
}
