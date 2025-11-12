\\# multiple-inheritance
\\only use to tourbo c++

#include<iostream>

#include<conio.h>

Class Student

{

protected:

int roll;

public:

void get.roll (int m)
{
roll=m;

}

void display-roll()

{

cout<<"\n noll no. ="<< roll:

}

};

class mante: public student
{
protected:

int m1, m2;

public:

void get.mark (int p,intq)
{
m1=p;
m2=q;
}
void display-mark()

{

cout<<" \n m,="<mi;

couta<<" \n ma"<<ma;.

}

};

class pratical
{
protected:

int m3;

public :

void get.prac (int)

m3=r;

}

void display.prac()
{
cout<<" \n m₃="<<m3;
}

};

class final: public mark: public pratical
{
int total

public:

void display()
{
total= m1+m2+m3;

display-roll();
display-roll();
display.prac();
cout<<total;
}
};

main()
{
    final obj;
    obj.get-roll(3001)
    obj.display();
    
}
