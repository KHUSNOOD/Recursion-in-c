# Recursion-in-c
// *********Basic of recursion*******
#include <iostream>
using namespace std;
void fun1(int n){
    if(n>0){
        cout<<n<<endl;
        fun1(n-1);
    }
}

int main() {
    // Write C++ code here
    //cout << "Hello world!";  
    int x=4;
    fun1(x);
    cout<<"khusnood"<<endl;
    return 0;
}
