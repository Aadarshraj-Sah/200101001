# Aadarshraj Sah
## 200101001



| Event name    | Event Dates    |Gone through the resources|
| ------------- |:-------------:| -----:                    |
| OPEN SOURCE   | 10/5/2021     | YES                       |
| COMPETITIVE CODING| 11/5/2021      | YES          |
| DESIGN | 12/5/2021    |   NO                    |
|GAME DEVELOPMENT | 13/5/2021 | NO
|WEB DEVELOPMENT | 14/5/2021 | NO |
|MACHINE LEARNING | 15/5/2021 | NO|
|APP DEVELOPMENT | 16/5/2021 | NO |




#include <iostream>
#include <string>
using namespace std;

int main() {
    char a;
    int ans=0;
    
    string st ="AadarshrajSah" ;
    for (int i=0; i < st.length(); i++){
        a = st[i];
        ans+=int(a);
    
    }
    cout<<"Sum of ASCII values of my name is = "<<ans<<endl;
    return 0;
}

