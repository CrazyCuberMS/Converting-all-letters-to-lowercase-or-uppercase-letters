# Converting-all-letters-to-lowercase-or-uppercase-letters #

```C++
#include <iostream>
using namespace std;
int main()
{ 
    string a,b;
    cin>>a>>b;
    transform(a.begin(), a.end(), a.begin(), ::tolower);
    transform(b.begin(), b.end(), b.begin(), ::toupper);
}
```
