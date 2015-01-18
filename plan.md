6. Pointer 
Memory menagement CH14. 263-376p
Reference(321p-323p)

ref vs (const) pointer
http://stackoverflow.com/questions/57483/what-are-the-differences-between-a-pointer-variable-and-a-reference-variable-in/57492#57492
http://stackoverflow.com/questions/2336230/difference-between-const-pointer-and-reference

c++ ref vs c++ ref
http://stackoverflow.com/questions/979814/c-references-and-java-references
pass by value or by ref

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
CH11. Class

Point class
Private, Public
Fraction class

http://cs.calvin.edu/activities/books/c++/engr-sci/LabExercises/Lab12/exercise.html



gcf, lcd
add sub

+

zero handling 
try/catch (237p-240p)
http://www.cs.uky.edu/~paulp/CS216F12/CS216Exceptions.htm

CH12. constructor
overloading 227-230p
constructor
Fraction constructor
copy constructor
string => fraction
Ch13. Operator  overloading

member vs global

friend

efficiency with ref

point class

Fraction class

working with other types // =
http://www.cplusplus.com/doc/tutorial/typecasting/
operator ==

Print member

cout 
http://www.cplusplus.com/reference/iostream/cout/

osteam
https://gcc.gnu.org/onlinedocs/libstdc++/libstdc++-html-USERS-3.4/ostream-source.html

iosream
https://gcc.gnu.org/onlinedocs/gcc-4.6.2/libstdc++/api/a00911_source.html

Ch14 string
deep copy

Ch15.
linked list
smart pointer
stack

CH16. STL
list template




