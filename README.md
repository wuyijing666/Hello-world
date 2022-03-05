(2.16)
#include <iostream>

using namespace std;

int main()
{
    int n,s,v;
    cin>>n;
    for (;n<=10;n++)
    {
        s=n*n;
        v=n*n*n;
        cout << n << "\t" << s << "\t" << v <<endl;
    }
    return 0;
}

(2.17)
#include <iostream>

using namespace std;

int main()
{
    cout << "1 2 3 4" ;
    return 0;
}


#include <iostream>

using namespace std;

int main()
{
    cout << "1 " << "2 " << "3 " << "4 ";
    return 0;
}


 #include <iostream>

using namespace std;

int main()
{
    cout << "1 ";
    cout << "2 ";
    cout << "3 ";
    cout << "4\n";
    return 0;
}

(2.18)
#include <iostream>

using namespace std;

int main()
{
    int x,y;
    cin >>x>>y;
    if(x==y)
    {
        cout << "These numbers are equal";
    }
    else if(x>y)
    {
        cout << x << " " << "is large";
    }
    else
    {
        cout << y << " " << "is large";
    }
    return 0;
}

(2.19)
#include <iostream>

using namespace std;

int main()
{
    int a,b,c,x,y,z;
    int max=0,min=0;
    cin>>a>>b>>c;
    x=a+b+c;
    y=(a+b+c)/3;
    z=a*b*c;
    if(a>b)
    {
        max=a,min=b;
    }
    else
    {
        max=b,min=a;
    }
    if(c>max)
    {
        max=c,min=min;
    }
    else max=max;
    cout <<"sum is " << x <<endl;
    cout <<"averager is " << y <<endl;
    cout <<"product is " << z <<endl;
    cout <<"smallest is " << min <<endl;
    cout <<"largest is " << max <<endl;
    return 0;
}

(2.20)
#include <iostream>

using namespace std;

int main()
{
    int r;
    double d,c,s;
    double pi=3.14159;
    cin >> r;
    d=2*r;
    c=2*pi*r;
    s=pi*r*r;
    cout <<"d="<< d <<endl;
    cout <<"c="<< c <<endl;
    cout <<"s="<< s <<endl;
    return 0;
}

(2.21)
#include <iostream>

using namespace std;

int main()
{
    cout << "*********" <<endl;
    cout << "*       *" <<endl;
    cout << "*       *" <<endl;
    cout << "*       *" <<endl;
    cout << "*       *" <<endl;
    cout << "*       *" <<endl;
    cout << "*       *" <<endl;
    cout << "*       *" <<endl;
    cout << "*********" <<endl;
    return 0;
}

#include <iostream>

using namespace std;

int main()
{
    cout << "   ***   " <<endl;
    cout << " *     * " <<endl;
    cout << "*       *" <<endl;
    cout << "*       *" <<endl;
    cout << "*       *" <<endl;
    cout << "*       *" <<endl;
    cout << "*       *" <<endl;
    cout << " *     * " <<endl;
    cout << "   ***   " <<endl;
    return 0;
}

#include <iostream>

using namespace std;

int main()
{
    cout << "  *  " <<endl;
    cout << " *** " <<endl;
    cout << "*****" <<endl;
    cout << "  *  " <<endl;
    cout << "  *  " <<endl;
    cout << "  *  " <<endl;
    cout << "  *  " <<endl;
    cout << "  *  " <<endl;
    cout << "  *  " <<endl;
    return 0;
}

#include <iostream>

using namespace std;

int main()
{
    cout << "    *    " <<endl;
    cout << "   * *   " <<endl;
    cout << "  *   *  " <<endl;
    cout << " *     * " <<endl;
    cout << "*       *" <<endl;
    cout << " *     * " <<endl;
    cout << "  *   *  " <<endl;
    cout << "   * *   " <<endl;
    cout << "    *    " <<endl;
    return 0;
}

(2.23)
#include <iostream>

using namespace std;

int main()
{
    int a,b,c,d,z;
    int max=0,min=0;
    cin>>a>>b>>c>>d>>z;
    {
        if(a<b)
        max=b,min=a;
        else max=a,min=b;
    }
    {
        if(c<max)
        max=max;
        else max=c;
    }
    {
        if(d<max)
        max=max;
        else max=d;
    }
    {
        if(z<max)
        max=max;
        else max=z;
    }
    {
        if(c<min)
        min=c;
        else min=min;
    }
    {
        if(d<min)
        min=d;
        else min=min;
    }
    {
        if(z<min)
        min=z;
        else min=min;
    }
    cout<<"max:"<<max<<endl;
    cout<<"min:"<<min<<endl;

    return 0;
}

(2.24)
#include <iostream>

using namespace std;

int main()
{
    int n;
    cin >>n;
    if(n%2==0)
    {
        cout <<"是偶数"<<endl;
    }
    else cout <<"是奇数"<<endl;
    return 0;
}

(2.25)
#include <iostream>

using namespace std;

int main()
{
    int x,y;
    cin >>x>>y;
    if(x%y==0)
    {
        cout <<"x是y的倍数"<<endl;
    }
    else cout <<"x不是y的倍数"<<endl;
    return 0;
}

(2.27)
#include <iostream>

using namespace std;

int main()
{
    char c;
    cin>>c;
    cout <<(int)c <<endl;
    return 0;
}

(2.28)
#include <iostream>

using namespace std;

int main()
{
    int a,b,c,d,e,z;
    cin>>z;
    a=z/10000;
    b=z%10000/1000;
    c=z%1000/100;
    d=z%100/10;
    e=z%10;
    cout <<a<<"   "<<b<<"   "<<c<<"   "<<d<<"   "<<e<<"   "<<endl;
    return 0;
}

(2.29)
#include <iostream>

using namespace std;

int main()
{
    int n,s,v;
    cin>>n;
    for (;n<=10;n++)
    {
        s=n*n;
        v=n*n*n;
        cout << n << "\t" << s << "\t" << v <<endl;
    }
    return 0;
}
