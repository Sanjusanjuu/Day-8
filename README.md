#include <iostream>
#include <string>
using namespace std;
int stringLength(){
    string name;
    getline(cin,name);
    cout<<name.length();

}
int main(){
    stringLength();
}
