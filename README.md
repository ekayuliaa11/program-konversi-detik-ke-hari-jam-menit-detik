# program-konversi-detik-ke-hari-jam-menit-detik

    #include <iostream>
    using namespace std;
    int main ()
    {
    int s,hari,jam,menit,detik,sisa;
    cout <<"Konversi Detik ke hari,jam,menit,detik"; cout<<endl;
    cout <<"Masukkan detik = "; cin>>s;
    hari = s/3600/24;
    jam  = s/3600;
    sisa = s%3600;
    menit= s/60;
    detik= sisa%60;
    cout <<hari<<" Hari\n"<<jam<<" Jam\n"<<menit<<" Menit\n"<<detik<<" Detik\n"<<endl;
    return 0;
    }




hasil program
![img](https://github.com/ekayuliaa11/program-konversi-detik-ke-hari-jam-menit-detik/blob/master/hasil%20konversi%20detik.png?raw=true)
