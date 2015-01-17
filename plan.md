6. Pointer 

Reference(321p-323p)

ref vs (const) pointer
http://stackoverflow.com/questions/57483/what-are-the-differences-between-a-pointer-variable-and-a-reference-variable-in/57492#57492
http://stackoverflow.com/questions/2336230/difference-between-const-pointer-and-reference

c++ ref vs c++ ref
http://stackoverflow.com/questions/979814/c-references-and-java-references

pass by pointer is using actually a copy constructor.
```
#include <iostream>
using namespace std;
void test(int * c){
    cout<<"test:"<<&c<<endl;
}

int main(int argc, const char * argv[]) {
    // insert code here...
    int * c=new int;
    *c=1;
    cout<<"main:"<<&c<<endl;
    test(c);
    return 0;
}
```
