1)
#include <iostream>
#include <string>
using namespace std;
int stringLength(const string &str){
    return str.length();
}
int main(){
    string st="HEllo, World!";
    cout<<stringLength(st)<<endl;
    string st1="Good night!";
    cout<<stringlength(st1);
}

2)
#include <iostream>
#include <string>
using namespace std;
int countCharacter(const string &str,char ch){
    int count=0;
    int a=str.length();
    for(int i=0;i<a;i++){
        if(str[i]==ch){
            count++;
        }
    }
    return count;
}
int main(){
    string str1="Hello, World";
    char c='l';
    cout<<countCharacter(str1,c);
}

3)
#include <iostream>
#include <string>
using namespace std;
string cocatestrings(string &str1, string &str2){
    return str1+str2;
}
int main(){
    string st1="Hello, ";
    string str2="World!";
    cout<<concatestrings(str1,str2);
}
