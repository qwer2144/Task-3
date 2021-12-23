//# Task-3
#include <iostream>
using namespace std;
 
int main()
{
    int i=0;
    while (!i)
    {
        float a, b, c, d, e, f;
        float n, m, p, o, r;
        cout << "Введите последовательность шести чисел: " << endl;
        cin >> a >> b >> c >> d >> e >> f;
        if(f == 0)
        {
            n = a + b;
            m = b + c;
            p = c + d;
            o = d + e;
            r = e + f;
            cout << "Новая последовательность: " << endl;
            cout <<  n  <<  m  <<  p  <<  o  <<  r  <<  f  << endl;
        }
        else
            cout << "Ошибка. Попробуйте снова. " << endl;
        
        cout << "Для расчета введите 0, чтобы закончить нажмите 1 ";
        cin >> i;
    }
system("pause");
return 0;
}
