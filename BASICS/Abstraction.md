it  hides the low level concept like low level implementation and only provides an function or  interface which we can use without knowing HOW that works internally, we only need to know WHAT that function does rather than how 

example : 

```cpp
#include <iostream>
#include <algorithm>

using namespace std;
int main(){
	int arr[] = {4,2,8,1,3};
	
	sort(arr, arr / 5);
	
	for (int i =0; i<5; i++){
		cout << arr[i] << " ";
	}
	return 0;
}
```

here we have used the sort () 
-  but we did not write the sorting algortihm 
-  so basically we have used the funciton provided C++ starndard library 
- we should know what does this does 


