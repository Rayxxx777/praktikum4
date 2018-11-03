#praktikum4

1. menentukan bilangan terbesar dari dua bilangan yang dimasukan
2. jika nilai a<b maka yang terbesar b, jika tidak maka sebaliknya
3. dengan masukan data inputan sebagai berikut.


#include <iostream>
using namespace std;

int main()
{
    int a,b;
        cout<< "mencari Bilangan terbesar dari dua bilangan yang diinputkan"<<endl;
        cout<< "input Bilangan A : ";
        cin>>a;
        cout<< "input Bilangan B : ";
        cin>>b;

        cout<< "hasilnya Adalah : ";
            if(a<b){
                    cout<<"B Terbesar";
            }else if(a>b){
                    cout<<"A Terbesar";
            }else
            cout<<"Tidak Ada";

        return 0;
}

![alt tag](https://raw.githubusercontent.com/Rayxxx777/praktikum4/master/praktikum4.png)