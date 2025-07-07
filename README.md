# Watching-Movies-at 2x



---

### ✅ **C++ Code (No Comments):**

```cpp
#include <iostream>
using namespace std;

int main() {
    int X, Y;
    cin >> X >> Y;
    int timeSpent = (Y / 2) + (X - Y);
    cout << timeSpent << endl;
    return 0;
}
```

---

### 💡 **Explanation:**

* **X** = total duration of the movie (in minutes)
* **Y** = Chef watches first Y minutes at **2x speed**, so he spends **Y / 2** minutes on that part.
* Remaining part: **X - Y** minutes watched at normal speed.

So, **total time spent** =
→ `(Y / 2)` (fast part) + `(X - Y)` (normal part)

---

### 📥 Example Input:

```
100 20
```

### 📤 Output:

```
90
```

### ✅ Why?

* First 20 minutes at 2x → takes 10 minutes
* Remaining 80 minutes at normal speed → takes 80 minutes
* Total = 10 + 80 = **90 minutes**

