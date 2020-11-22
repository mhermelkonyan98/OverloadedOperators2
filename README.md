# OverloadedOperators2
You are given a class - Complex.

class Complex
{
public:
    int a,b;
};
Operators are overloaded by means of operator functions, which are regular functions with special names. 
Their name begins with the operator keyword followed by the operator sign that is overloaded. The syntax is:

type operator sign (parameters) { /*... body ...*/ }
You need to overload operators + and << for the Complex class.

The operator + should add complex numbers according to the rules of complex addition:

(a+ib)+(c+id) = (a+c) + i(b+d)
Overload the stream insertion operator << to add "a+ib" to the stream:

cout<<c<<endl;

Sample Input

3+i4
5+i6
Sample Output

8+i10
Explanation

