# 110---NEARLY-LUCKY-NUMBER-CODEFORCES
 HERE IS THE MY OWN SOLUTION OF THIS CF PROB

 #include <bits/stdc++.h>
using namespace std;

int main() {
    string s;
    cin >> s;
    
    int c = 0;
    
    for (int i = 0; i < s.length(); i++) {  // Fixed typo in for-loop
        if (s[i] == '4' || s[i] == '7')
            c++;
    }

    cout << ((c == 4 || c == 7) ? "YES" : "NO") << endl;  // Print result
    return 0;
}

