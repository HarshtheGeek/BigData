# BigData - 

``` cpp
#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter number of rows: ";
    cin >> n;

    for (int i = 1; i <= n; i++) {         // For Rows
        for (int j = 1; j <= i; j++) {     // For Columns
            cout << "* ";
        }
        cout << endl;
    }

    return 0;
}

```


**Output** : 
* 
* * 
* * * 
* * * * 
* * * * * 
