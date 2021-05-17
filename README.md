# set-k-th-bit

#include<bits/stdc++.h>
using namespace std;

class Aditya
{
public:
int setKthBit(int N, int K)
    {
        return N|(1 << K);
    }
    
};

int main()
{
int t;
cin >> t;
while(t--)
{
int K.N;
cin >> K >> N;
Aditya ob;
int ans = ob.setKthBit(int N, int K);
cout << ans << end;
}
return 0;





