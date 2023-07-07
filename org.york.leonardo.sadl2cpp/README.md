# Generated CPP Files
The generated cpp files from the [SADL model](model/sample.sadl) under the `model` directory. 

```cpp
/*** Output for dep1_p1top2TCP ***/

#include <iostream>
#include <string>

int main() {

    std::cout << "Output for dep1_p1top2TCP!";
    
    string proc1 = "cont1";
    string proc2 = "cont2";

    string serverIP = "0.0.0.0";
    string serverPort = "8100";

    
    return 0;
}

```

```cpp
/*** Output for dep1_p1top2UDP ***/

#include <iostream>
#include <string>

int main() {

    std::cout << "Output for dep1_p1top2UDP!";
    
    string proc1 = "cont1";
    string proc2 = "cont2";

    string iP1 = "127.0.0.1";
    string port1 = "8100";
    string iP2 = "127.0.0.1";
    string port2 = "8101";

    return 0;
}
```